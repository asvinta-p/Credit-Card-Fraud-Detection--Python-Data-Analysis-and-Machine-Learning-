# Credit Card Fraud Detection - Python: Data Analysis and Machine Learning Project

## Overview
Built an end-to-end machine learning project to detect fraudulent credit card transactions. 
Built a complete pipeline from data cleaning to model deployment as a web application using streamlit.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost, Streamlit, Joblib

## Process
- Performed EDA, data cleaning, missing value imputation, and IQR-based outlier treatment
- Applied SMOTE oversampling to handle class imbalance
- Trained and compared 9 classification models
- Performed Hyperparameter tuning using GridSearchCV to improve model performance
- Deployed the final model as a streamlit web application to enable real-time fraud monitoring

## Results
- XGBoost selected as best model because of its high accuracy,strong fraud detection capability and better generalization performance after comparing 9 classification models.
- Full pipeline from raw data to deployed application
- Real-time fraud prediction from user inputs via Streamlit

## Files
- ML_main_project(1).ipynb — main notebook
- credit_card_fraud_dataset-5.csv - dataset
