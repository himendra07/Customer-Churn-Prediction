**Customer Churn Prediction — Machine Learning Project**
*Project Overview*

This project predicts customer churn (whether a customer is likely to leave a service) using the Telco Customer Churn dataset.
It demonstrates the end-to-end data science workflow — from data preprocessing and visualization to model training, evaluation, and deployment readiness.

*Objective*

To help companies identify customers likely to churn and take proactive retention actions using machine learning models.

*Key Steps*

Data Loading & Cleaning

Handled missing values in TotalCharges

Encoded categorical features using one-hot and label encoding

Exploratory Data Analysis (EDA)

Distribution of churn vs tenure, contract type, payment method

Correlation heatmap for numeric features

Feature Engineering

Normalized numerical data using StandardScaler

Converted binary Yes/No features to 0/1

Model Building

Logistic Regression

Random Forest Classifier

Compared accuracy, precision, recall, and F1-score

Model Evaluation

Confusion Matrix

ROC Curve and AUC

Feature Importance visualization

Model Saving

Exported trained Random Forest model with joblib for deployment

*Tech Stack*

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Joblib

Tools: Jupyter Notebook, Power BI (for dashboard visualization)

*Results*

Random Forest model achieved ~88% accuracy

Logistic Regression model achieved ~82% accuracy

ROC AUC = 0.90 (strong model performance)

Key churn indicators: Contract Type, Tenure, Monthly Charges