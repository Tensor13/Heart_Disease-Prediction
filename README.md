# Heart Disease Prediction
 This repository contains a Jupyter Notebook implementation for predicting the likelihood of heart disease using machine learning models. The project involves data preprocessing, feature engineering, and the application of supervised learning algorithms to build a predictive model.
 ## Project Overview
  Heart disease is a leading cause of death worldwide, and early prediction can help in timely intervention and management. This notebook demonstrates how to leverage machine learning techniques to predict heart disease based on patient data such as age, gender, cholesterol levels, and other medical attributes.
 ## Features
  * ### Data Preprocessing: Handles missing values, encodes categorical features, and scales numerical features.
  * ### Exploratory Data Analysis (EDA): Visualizes correlations and distributions of key attributes.
  * ### Model Training: Trains various supervised learning models including logistic regression, decision trees, and more.
  * ### Model Evaluation: Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.

## Dataset Description 
 Heart disease is a leading cause of death worldwide, and early prediction can help in timely intervention and management. This notebook demonstrates how to leverage machine learning techniques to predict heart disease based on patient data such as age, gender, cholesterol levels, and other medical attributes.
 ## Features
  * Data Preprocessing: Handles missing values, encodes categorical features, and scales numerical features.
  * Exploratory Data Analysis (EDA): Visualizes correlations and distributions of key attributes.
  * Model Training: Trains various supervised learning models including logistic regression, decision trees, and more.
  * Model Evaluation: Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.

## Dataset Description
The dataset used in this project is structured and contains several key attributes relevant to predicting heart disease. Below is an explanation of each attribute:

* 1.Age: Age of the patient in years. This is a critical factor as the risk of heart disease increases with age.

* 2.Sex: Gender of the patient, typically encoded as 1 for male and 0 for female.

* 3.Chest Pain Type (cp): Represents the type of chest pain experienced:
   * 0: Typical angina
   * 1: Atypical angina
   * 2: Non-anginal pain
   * 3.Asymptomatic

* 4.Resting Blood Pressure (trestbps): Blood pressure in mm Hg when the patient is at rest.

* 5.Serum Cholesterol (chol): Cholesterol level in mg/dL, a key indicator of cardiovascular health.

* 6.Fasting Blood Sugar (fbs): Indicates whether fasting blood sugar > 120 mg/dL:
   * 1: True
   * 2 0: False

* 7.Resting Electrocardiographic Results (restecg): Results of the ECG at rest:
   * 0: Normal
   * 1: Having ST-T wave abnormality (e.g., T wave inversions or ST elevation/depression > 0.05 mV)
   * 2: Showing probable or definite left ventricular hypertrophy

* 8.Maximum Heart Rate Achieved (thalach): Maximum heart rate achieved during exercise.

* 9.Exercise-Induced Angina (exang): Indicates if the patient experiences angina during exercise:
   * 1: Yes
   * 0: No

* 10.Oldpeak: ST depression induced by exercise relative to rest, which helps measure heart stress.

* 11.Slope: Slope of the peak exercise ST segment:
    * 0: Upsloping
    * 1: Flat
    * 2: Downsloping

* 12.Number of Major Vessels (ca): Number of major blood vessels (0-3) colored by fluoroscopy.

* 13.Thalassemia (thal): A blood disorder measured in this dataset as:
   * 0: Normal
   * 1: Fixed defect
   * 2: Reversible defect

* 14.Target: Indicates the presence of heart disease:
    * 1: Heart disease present
    * 0: No heart disease

The dataset provides a mix of numerical and categorical features, enabling the application of various preprocessing and machine learning techniques to build robust predictive models.
## Requirements

To run the notebook, you will need the following Python libraries:
 * pandas
 * numpy
 * matplotlib
 * seaborn
 * scikit-learn
 * Jupyter Notebook or JupyterLab
## Results
The notebook includes:

 * Training results for multiple models.
 * Comparison of model performance.
 * Insights from feature importance analysis.
