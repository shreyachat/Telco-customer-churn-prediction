# Telco-customer-churn-prediction
End-to-end customer churn prediction project using machine learning with business insights and deployment-ready pipeline.

# Customer Churn Prediction – Telecom Industry

## Problem Statement
Customer churn is a critical challenge in the telecom industry, directly impacting revenue and customer lifetime value.
This project aims to predict customer churn and identify key factors influencing customer attrition, enabling proactive
retention strategies.

## Dataset
- Telco Customer Churn Dataset
- Total Records: 7,043 customers
- Target Variable: Churn (Yes/No)

## Approach
The project follows an end-to-end machine learning workflow:
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Model building using machine learning algorithms
5. Model evaluation and comparison
6. Feature importance analysis
7. Business recommendations

## Models Used
- Logistic Regression (baseline model)
- Random Forest Classifier (final selected model)

## Evaluation Metrics
- ROC-AUC Score
- Precision, Recall, F1-score
- Confusion Matrix

## Key Insights
- Customers on month-to-month contracts have the highest churn risk
- Low-tenure customers are more likely to churn
- Higher monthly charges significantly increase churn probability

## Business Recommendations
- Introduce early engagement and onboarding programs for new customers
- Encourage customers to switch to long-term contracts through incentives
- Offer personalized plans and discounts to high-value customers

## Model Deployment Readiness
The final preprocessing and modeling pipeline was serialized using `joblib`, making it reusable for batch scoring or
future production deployment.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
