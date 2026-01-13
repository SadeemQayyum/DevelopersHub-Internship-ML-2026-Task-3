**Task 3: Heart Disease Prediction Using Logistic Regression**

**Objective**

The objective of this task is to predict whether a patient has heart disease based on medical attributes. This task focuses on applying a classification based machine learning model to analyze healthcare data and evaluate prediction performance.

**Dataset Description**

The dataset is downloaded using KaggleHub and contains medical records of patients.
It includes the following features:

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol level
* Fasting blood sugar
* Resting ECG results
* Maximum heart rate
* Exercise induced angina
* ST depression
* Slope of peak exercise
* Number of major vessels
* Thalassemia
* Target variable indicating heart disease

**Tools and Libraries Used**

* Python
* Pandas for data handling
* KaggleHub for dataset download
* Seaborn for data visualization
* Matplotlib for plotting graphs
* Scikit learn for machine learning
* Steps Performed
* Downloaded the dataset using KaggleHub
* Loaded the dataset into a Pandas DataFrame
* Checked dataset structure and missing values
* Performed exploratory data analysis
* Split the dataset into training and testing sets
* Trained a Logistic Regression model
* Evaluated model accuracy
* Generated confusion matrix
* Plotted ROC curve and calculated AUC score
* Analyzed feature importance

**Results and Observations**

* The model achieved an accuracy of 79 percent
* ROC AUC score of 0.88 indicates strong classification performance
* The model correctly identified most patients with heart disease
* Some misclassifications occurred due to overlapping medical symptoms

**Conclusion**

This task demonstrates that Logistic Regression is effective for heart disease classification. The model provides reliable performance and can assist in early risk assessment. However, it should be used as a supporting tool and not as a replacement for medical diagnosis.

**How to Run**

* Open the Jupyter Notebook file
* Run each cell sequentially
* Ensure required libraries are installed
