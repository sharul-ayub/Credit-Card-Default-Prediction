# 💳 Credit Card Default Prediction
<p align="justify">
This project develops a machine learning solution to predict whether a credit card customer will default on their next payment. The objective is to support financial institutions in improving credit risk management, reducing financial losses, and enabling proactive decision-making.

The model leverages historical customer data, including demographic information, credit limits, billing history, and repayment behavior, to identify high-risk customers.
</p>

## Business Problem
Credit card default poses significant financial and operational risks to financial institutions. Late or missed payments can lead to:

- Increased bad debt and financial loss  
- Inefficient resource allocation in collections  
- Reduced profitability  
- Regulatory and compliance risks 

This project aims to provide a predictive model that enables early identification of potential defaulters, allowing institutions to take preventive actions such as credit limit adjustments or targeted customer engagement.

## Dataset
- Source: UCI Machine Learning Repository  
- Records: 30,000 customers  
- Features: 25 variables  
- Target: Default payment (1 = default, 0 = non-default)  

The dataset includes:
- Demographics (age, gender, education, marital status)  
- Credit information (credit limit)  
- Repayment history (PAY_1 to PAY_6)  
- Billing amounts (BILL_AMT1 to BILL_AMT6)  
- Payment amounts (PAY_AMT1 to PAY_AMT6)  

The dataset is highly imbalanced, with approximately 22.1% default cases and 77.9% non-default cases.

## Workflow
1. Data Understanding
2. Data Cleaning
3. Feature Engineering
4. Model Training
5. Evaluation

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM (Best Model)

## Best Model Performance
- Accuracy: 87.9%
- Precision: 91.9%
- Recall: 83.2%
- F1 Score: 87.3%
- ROC-AUC: 0.940

## 📈 Key Features
- credit_utilization
- max_delay
- pay_bill_ratio_avg

