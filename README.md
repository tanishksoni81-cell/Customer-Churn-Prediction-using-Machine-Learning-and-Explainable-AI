# Customer-Churn-Prediction-using-Machine-Learning-and-Explainable-AI
This project predicts customer churn for a subscription-based telecom company using the IBM Telco Customer Churn dataset.  The objective is to identify customers likely to churn, understand the reasons behind churn, and provide actionable retention recommendations.
Business Problem

Customer churn directly impacts revenue and growth.

The goal of this project is to:

Predict customers likely to churn
Understand the factors driving churn
Help business teams prioritize retention efforts
Estimate revenue at risk
Dataset

Dataset: IBM Telco Customer Churn Dataset

Customers are labeled as:

Churn = Yes
Churn = No

Target Variable:

Churn
Project Workflow
1. Exploratory Data Analysis (EDA)
Missing value analysis
Churn distribution analysis
Contract analysis
Customer tenure analysis
Service adoption analysis
2. Feature Engineering

Custom features created:

Average Revenue Per Month
Customer Lifetime Value Proxy
Service Count
Contract Risk Score
Tenure Segment
Churn Risk Indicators
3. Model Development

Models evaluated:

Logistic Regression
Random Forest
XGBoost
LightGBM

Final model selected:
XGBoost Classifier

Evaluation metrics:
Accuracy
Precision
Recall
F1 Score
ROC-AUC

4. Explainable AI
Implemented SHAP to:
Understand model decisions
Rank churn drivers
Explain customer-level predictions
Support retention strategies

Key churn drivers:
Contract Risk Score
Customer Tenure
Monthly Charges
Service Count

5. Power BI Dashboard

Executive Overview
Churn Rate
Revenue at Risk
Customer Segmentation
Contract Analysis

Explainable AI Dashboard
SHAP Feature Importance
Risk Factor Analysis
Retention Recommendations

Technology Stack
Programming
Python
Libraries
Pandas
NumPy
Scikit-Learn
XGBoost
SHAP
Matplotlib
Seaborn
Visualization
Power BI
Version Control
GitHub
Results

The project successfully:

Predicted customer churn
Identified high-risk customers
Explained model predictions
Generated retention recommendations
Visualized business insights through Power BI
Future Improvements
FastAPI deployment
Real-time churn scoring
Automated retention workflows
Cloud deployment
Model monitoring
Author

Tanishk Soni

LinkedIn: www.linkedin.com/in/
tanishk-soni-878016248

GitHub: tanishksoni81-cell
