# credit-risk-classification
This challenge contains the Credit_Risk folder, which includes the data in lending_data.csv, and a Jupyter Notebook file called credit_risk_classification.ipynb, which creates a model based on the data. This challenge also contains an Analysis report, found below in the ReadMe.

# Module 20 Report 

## Overview of the Analysis

Machine learning techniques are used to train and evaluate a model based on a loan risk. A dataset containing historical lending activity from a peer-to-peer lending services company is used to build a model to identify which borrowers have good credit. For the analysis, the dependent variable was the loan status. At the same time, the independent variables were the loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. A Logistic Regression model was created, and the original data was fit to this model.


## Results
* Machine Learning Model: Logistic Regression
  * The precision for the Logistic Regression was 100% for predicting healthy loans and 85% for predicting high-risk loans.
  * The recall scores for the Logistic Regression were 99% for predicting healthy loans and 91% for predicting high-risk loans.
  * The balanced accuracy score for the Logistic Regression model was 95%.

## Summary

* It is more important to predict high-risk loans than healthy loans.
* For the high-risk loans, the Logistic Regression model with the original data had an f1-score of 88%, meaning that there is moderately high accuracy in relation to precision and recall. 
* For the healthy loans, the f1-score was 100%, meaning that there is high accuracy in relation to precision and recall.
* Based on the f1-scores of the high-risk loans and the healthy loans from the Logistic Regression model with the original data, I would recommend this model.
