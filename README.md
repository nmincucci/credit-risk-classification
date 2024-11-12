# Credit Risk Classification

## Overview of the Analysis

### Purpose
The goal of this analysis is to develop a model that predicts the likelihood of loan default, categorizing loans as either high risk or low risk.

### Financial Data
The model utilizes several key features, including:
- Loan size
- Interest rate
- Borrower income
- Debt-to-income ratio
- Number of accounts held
- Derogatory marks
- Total debt

### Methods
The analysis involved splitting the financial data into training and test datasets. A logistic regression algorithm was applied to the training data, and predictions were generated using the test data. The model's predictions were then evaluated against the actual loan statuses, resulting in a confusion matrix and classification report.

## Results

### Logistic Regression Model Performance
- **Accuracy:** 99%
- **Precision:** 
  - 100% for healthy loans
  - 87% for high-risk loans
- **Recall:** 
  - 100% for healthy loans
  - 95% for high-risk loans

The model demonstrates excellent performance, with high scores in accuracy, precision, and recall. While there is a slightly higher risk of false positives compared to false negatives, overall, the model is reliable.

## Summary
The logistic regression model has shown strong performance metrics, making it a viable option for implementation. With an accuracy of 99%, the model minimizes the risk of losses from defaulted loans, although there is a higher likelihood of false positives. Given the high precision and recall scores, both false positives and false negatives are unlikely.
