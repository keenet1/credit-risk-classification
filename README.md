# Credit Risk Classification

Note: The completed assignment is located in the folder titled "Credit_Risk" and is titled "credit_risk_classification.ipynb"

## Overview of the Analysis

The purpose of this activity was to use various techniques to train and evaluate a machine learning model based on loan risk. The activity used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that could identify the creditworthiness of borrowers and then classify the credit risk predictions.

The target of the data set was the loan status. The features of the data set that were used to predict the loan status were: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt.

For the target values of loan status, a value of 0 was used to indicate that the loan was healthy, whereas a value of 1 meant that the loan had a high risk of defaulting.

The process used for creating and testing the model included the following steps:
- Reading the original data into a Pandas DataFrame
- Splitting the data into training and testing Sets
- Creating a Logistic Regression Model with the Original Data
- Evaluating the model's performance using both a confusion matrix and a classification report

## Results

The following screen captures show the classification report as well as the accuracy results of the model:

![Screenshot 2023-11-16 at 4 20 53 PM](https://github.com/keenet1/credit-risk-classification/assets/137319054/22c64f26-4361-435a-a561-d659aa119ca1)

![Screenshot 2023-11-16 at 4 21 28 PM](https://github.com/keenet1/credit-risk-classification/assets/137319054/fc4f5b79-a6e4-4954-b71d-bbff1a06c030)

 - The logistic regression model predicts a healthy (low-risk) loan with 100% precision and predicts a high-risk loan with 85% precision.
 - Overall, the model does well as can be seen from the high accuracy score of 99.18% as well as the balanced accuracy score of 95.20%.

## Summary
Based on the overall accurcy scores of the logistic regression model, along with its high degree of precision in correctly classifying healthy loans vs those that are at high risk of default, my recommendation is to use the logistic regression model.
