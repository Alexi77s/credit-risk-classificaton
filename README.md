# credit-risk-classificaton


## Overview of the Analysis
The purpose of the analysis is to determine if logistic regression can predict accurately on healthy vs high risk loans from orginal and oversampled data. 
The data contains 77,536 loans with columns that pertains to loan size, interest rate, borrower income, debt to income ratio number of accounts, derotary marks, total debt and loan status. Our focus will be the loan staus and will train the data. 

The stages of prediction will be processed with Machine Learning in preparign the data, separating data into labels and features, using train test split funtion to split into training and testing datasets. Also import Logistic Regression from SKLearns, instantiate the model, fit model with training data, make predictions and evaluate it with accuracy score, confusiont matrix, and classification report. 

## Results


* Machine Learning Model 1: Original Logistic Regression
   * Accuracy Score: 0.95
  *Precision: Class (0): 1.00      Class(1): 0.85
  *Recall: Class (0):0.99          Class(1):0.91



* Machine Learning Model 2:Oversampled Logistic Regression
  * Accuracy Score: 0.99
  *Precision: Class (0): 1.00      Class(1): 0.84
  *Recall: Class (0):0.99          Class(1):0.99

## Summary

The Logistic Regression Model performed well for predicting the accuracy of healthy loans in both the orginal and oversampled model. 
However, for the high risk loans, the precision and recall for original model was low compared to the oversampled model which had a higher recall value and 0.01 lowers value for precision. 
The highly recommended version would be the oversampled model due the recall value in the high risk loans. 
