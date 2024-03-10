# Module 12 Report 

## Overview of the Analysis

This analysis developed machine learning models to predict the creditworthiness of borrowers based on historical lending data from a peer-to-peer lending services company. The goal was to use financial information provided by borrowers to predict whether a loan is healthy or high-risk.

The dataset contained various financial features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt, along with the loan status indicating whether the loan is healthy (0) or high-risk (1).

The stages of the machine learning process included data preprocessing, splitting the data into training and testing sets, model training using logistic regression, and model evaluation using accuracy, precision, and recall scores.

We used logistic regression as our machine learning algorithm to predict the loan status based on the provided financial features.

## Results

Machine Learning Logistic Regression Model:
Accuracy: 99%
Precision:
Label 0 (healthy loan): 100%
Label 1 (high-risk loan): 86%
Recall:
Label 0 (healthy loan): 99%
Label 1 (high-risk loan): 94%

## Summary

The logistic regression model performed very well in predicting both healthy and high-risk loans. It achieved an accuracy of 99%, indicating that the model correctly classified 99% of the loans. The precision and recall scores were also high for both labels, with precision of 100% for healthy loans and 86% for high-risk loans, and recall of 99% for healthy loans and 94% for high-risk loans.

In this instance, the logistic regression model was the only one tested. It has high accuracy, precision, and recall scores for both healthy and high-risk loans. However, the performance might depend on the problem we are trying to solve. For instance, if it's more important to correctly identify high-risk loans (label 1), then we might prioritize models with higher recall scores for label 1.

Overall, based on the results obtained, the logistic regression model appears to be a suitable choice for predicting loan creditworthiness in this scenario.
