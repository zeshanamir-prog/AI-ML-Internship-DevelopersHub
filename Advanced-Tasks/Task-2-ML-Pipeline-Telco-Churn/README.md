# Task 2: End-to-End ML Pipeline – Customer Churn Prediction

## Objective
Build a production-ready machine learning pipeline to predict customer churn
using preprocessing, model training, and hyperparameter tuning.

## Dataset
Telco Customer Churn Dataset
- Customer demographic and service usage data
- Target variable: Churn (Yes/No)

## Methodology
- Data cleaning and preprocessing
- Handling missing values
- Encoding categorical variables using OneHotEncoder
- Scaling numeric features using StandardScaler
- Built complete Pipeline using ColumnTransformer
- Trained Logistic Regression and Random Forest models
- Applied GridSearchCV for hyperparameter tuning
- Exported final model using joblib

## Results
- Logistic Regression provided a strong baseline.
- Hyperparameter tuning improved performance.
- Random Forest captured nonlinear patterns effectively.
- Entire pipeline is reusable and production-ready.

## Conclusion
This task demonstrates industry-level ML engineering practices
using Scikit-learn Pipeline API and model deployment preparation.
