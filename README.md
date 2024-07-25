# Module 12 Report

## Overview of the Analysis

In this analysis, we evaluated a logistic regression model to predict credit risk for loan applications. The objective was to classify loans into "healthy" or "high-risk" categories based on various financial metrics. The dataset included features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. Our target variable was `loan_status`, which indicates whether a loan is healthy (`0`) or high-risk (`1`).

**Machine Learning Process:**

1. **Data Preparation:** Loaded the dataset and separated it into features (`X`) and labels (`y`).
2. **Data Splitting:** Divided the data into training and testing sets.
3. **Model Training:** Used `LogisticRegression` to fit the model on the training data.
4. **Model Evaluation:** Evaluated the model's performance using accuracy, precision, and recall metrics.

## Results

* **Logistic Regression Model:**
    * **Accuracy:** 99%
    * **Precision:**
      - Healthy loans (`0`): 100%
      - High-risk loans (`1`): 85%
    * **Recall:**
      - Healthy loans (`0`): 99%
      - High-risk loans (`1`): 91%

## Summary

The logistic regression model performs exceptionally well with a 99% accuracy. It achieves perfect precision for healthy loans and strong performance for high-risk loans, balancing precision and recall effectively. This model is recommended for use as it effectively identifies both healthy and high-risk loans, supporting robust credit risk management. The performance indicates that it is suitable for predicting high-risk loans, which is crucial for minimizing financial risk.
