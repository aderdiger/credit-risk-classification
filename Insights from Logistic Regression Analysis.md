# Loan Default Prediction: Insights from Logistic Regression Analysis

## Overview of the Analysis

In this analysis, I aimed to develop a machine learning model using logistic regression to predict loan defaults based on financial data. The purpose of the analysis was to assist in risk assessment and decision-making processes in the lending industry. The dataset comprised various financial attributes of loan applicants, including loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt. The target variable was loan status, indicating whether the loan defaulted or not.

Exploration of the data revealed class imbalance, with a larger proportion of non-defaulting loans compared to defaulting ones. I followed standard stages of the machine learning process, including data preprocessing, feature engineering, model training, evaluation, and tuning, focusing solely on logistic regression as the chosen algorithm for the classification task.

## Results

* Logistic Regression:
    * Accuracy: 0.99
    * Precision:
        * Healthy Loans: 1.00
        * High-Risk Loans: 0.87
    * Recall:
        * Healthy Loans: 1.00
        * High-Risk Loans: 0.89

## Summary

The Logistic Regression model demonstrated strong overall performance with high accuracy and precision scores for both healthy loans and high-risk loans. However, it's notable that the model performed slightly better in predicting healthy loans compared to high-risk loans. This performance asymmetry suggests potential implications for decision-making, where correctly identifying high-risk loans might be of greater importance to mitigate financial losses.

Considering the model's balanced accuracy and robust precision-recall scores, I recommend further evaluation and potentially deployment of the Logistic Regression model for practical use. However, it's crucial to continuously monitor and refine the model's performance, especially in addressing class imbalance and adapting to evolving financial landscapes.
