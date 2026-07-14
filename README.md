# Developers-Hub-AI-ML-Internship-Phase2-

Task 2: End-to-End ML Pipeline with Scikit-learn Pipeline API

Objective:
The objective of this project is to build an end-to-end machine learning pipeline to predict customer churn using the IBM Telco Customer Churn dataset. The project demonstrates how to preprocess data, train classification models, optimize model performance using hyperparameter tuning, and create a reusable pipeline for predicting whether a customer is likely to churn.

Methodology / Approach:
- Loaded and explored the IBM Telco Customer Churn dataset.
- Performed data preprocessing by handling missing values and converting the target variable into numerical format.
- Identified numerical and categorical features.
- Built preprocessing pipelines using Scikit-learn's Pipeline and ColumnTransformer.
- Applied StandardScaler to numerical features and OneHotEncoder to categorical features.
- Trained two classification models: Logistic Regression and Random Forest.
- Evaluated both models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
- Performed hyperparameter tuning using GridSearchCV to improve model performance.
- Compared both models and saved the best-performing pipeline using Joblib.
- Used the saved pipeline to make predictions on new customer data.
  
Key Results / Observations:
- Successfully developed a complete end-to-end machine learning pipeline for customer churn prediction.
- Automated data preprocessing using Scikit-learn Pipeline and ColumnTransformer.
- Trained and compared Logistic Regression and Random Forest classifiers.
- Improved model performance through hyperparameter tuning using GridSearchCV.
- Exported the best-performing model as a reusable pipeline using Joblib.
- Demonstrated how the saved pipeline can be used to predict churn for new customer records, making the workflow suitable for real-world deployment.
