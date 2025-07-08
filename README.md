
# Customer Churn Prediction

This project analyzes customer data from a telecom company to understand and predict customer churn, that is, which customers are likely to cancel their service.


## Objectives

- Identify key features that influence customer churn
- Build a predictive model using Logistic Regression
- Help the company reduce churn through actionable insights

## 📊 Dataset Overview

- **Customer demographics** (age, partner, dependents)
- **Service details** (internet type, phone, streaming)
- **Contract type** (month-to-month, one year, two year)
- **Billing and payment** (monthly charges, paperless billing, payment method)
- **Churn status** (Yes or No)

## 🧪 Model Used

- **Logistic Regression** with:
  - L1 and L2 regularization
  - `class_weight='balanced'` to handle class imbalance
- Evaluated using **ROC AUC score** and **confusion matrix**


This dataset is detailed in:
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

Downloaded from:
https://community.ibm.com/accelerators/?context=analytics&query=telco%20churn&type=Data&product=Cognos%20Analytics