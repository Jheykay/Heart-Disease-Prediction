# Heart-Disease-Prediction
The repository contains python code for analyzing and predicting likelihood of heart disease in patients. The code utilizes various libraries such as scikit-learn, pandas, seaborn, matplotlib.pyplot to perform data analysis, visualization and predictions on patients.

##  Datasets Overview
The analysis is performed on a dataset named "project1_data.csv", which contains patients medical records from a clinic. The dataset includes information such as age, sex, chest pain type, fasting blood sugar, resting blood pressure, serum cholesterol in mg/dl, resting electrocardiographic results, maximum heart rate achieved, exercise induced angina, and thalassemia type etc.

## Data Preprocessing
The data preprocessing phase involves cleaning and preparing the dataset for model training. This includes handling missing values, handling outliers, and exploring relationships between features and target variable.

## Model Development
Two machine learning algorithms were utilized for the prediction of likelihood of heart disease in patients.

 1. Logistic Regression
 2. XGBoost Classifier

Hyperparameter tuning techniques such as GridSearchCV and BayesSearchCV were employed to optimize each model's performance.

## Model Evaluation
The performance of each model was assessed using various evaluation metrics, including confusion matrix visualization, classification reports, and key performance indicators such as R2 Score, Mean Squared Error, and Mean Absolute Error. Also Features distribution was assessed for the Logistic Regression.

## Conclusion
After thorough analysis and evaluation, the XGBoost Classifier emerged as the top-performing model, achieving an impressive accuracy of 96%. This model demonstrated superior predictive capabilities compared to the Logistic Regression, which achieved accuracies of 84%. The XGBoost Classifier is therefore recommended for predicting likelihood of heart disease in patients in this scenario.

for running the code, make sure to install the required packages listed in the requirements.txt using the command pip install -r requirements.txt
