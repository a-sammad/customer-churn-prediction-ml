# Customer Churn Prediction (Banking Sector)

## Overview
Customer churn prediction is a critical business problem in the banking industry. 
This project uses Machine Learning to predict whether a customer is likely to leave the bank based on demographic and financial attributes.

## Business Objective
Help banks identify high-risk customers early and take proactive retention actions.

## Dataset Features
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Estimated Salary
- Active Membership

## Machine Learning Approach
1. Data Cleaning & Feature Selection
2. Categorical Encoding
3. Train-Test Split
4. Random Forest Classification
5. Feature Importance Analysis

## Model Used
Random Forest Classifier

## Results
- Model predicts customer churn with strong accuracy.
- Feature importance highlights key churn drivers.

## Key Insights
Top factors influencing churn:
- Age
- Balance
- Credit Score
- Geography
- Number of Products

## Technologies
Python | Pandas | NumPy | Scikit-learn

## How to Run
```bash
pip install -r requirements.txt
python src/churn_model.py
