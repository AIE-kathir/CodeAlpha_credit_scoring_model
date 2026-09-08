Credit Scoring & Risk Prediction Model

A machine learning project that predicts whether a customer is Lower Risk or Higher Risk based on financial and credit-related information.

The project compares multiple classification algorithms and evaluates their performance using Precision, Recall, F1 Score, and ROC-AUC. The best-performing model is then saved using Joblib for future predictions.

📌 Project Overview

Credit risk assessment is an important task in the financial industry. This project demonstrates how machine learning can be used to analyze customer financial information and estimate their credit risk.

The model considers factors such as:

Age

Income

Employment years

Debt

Monthly expenses

Credit utilization

Late payments

Number of loans

Savings

Payment history score

🎯 Objectives

Build a machine learning model for credit risk prediction.

Perform basic feature engineering on financial data.

Compare different classification algorithms.

Evaluate models using multiple classification metrics.

Identify the best-performing model.

Save the trained model for future predictions.

Demonstrate prediction on a new customer.

🤖 Machine Learning Models

Three classification models are trained and compared:

1. Logistic Regression

The Logistic Regression model uses:

Median imputation

Standard scaling

Balanced class weights

Maximum 2,000 iterations

2. Decision Tree

The Decision Tree uses:

Median imputation

Maximum depth of 6

Minimum samples per leaf of 20

Balanced class weights

3. Random Forest

The Random Forest uses:

Median imputation

300 decision trees

Maximum depth of 8

Minimum samples per leaf of 8

Balanced class weights

🔮 Example Prediction

The notebook demonstrates prediction for a new customer using features such as:

Age: 30
Income: 50000
Employment Years: 5
Debt: 15000
Monthly Expenses: 2500
Credit Utilization: 0.30
Late Payments: 1
Loan Count: 2
Savings: 20000
Payment History Score: 85

The example prediction produced:

Predicted Risk: Lower Risk
Estimated higher-risk probability: 3.28%

This example is included to demonstrate how the trained model can be used for individual customer risk prediction.
