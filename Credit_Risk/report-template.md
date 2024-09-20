# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to create a supervised machine learning model that will predict if a loan is healthy (class 0) or high-risk (class 1). dataset of historical lending activity from a peer to peer lending service company will be used to build a model that can identify the creditworthiness of borrowers. 



## Results

Description of Logistic Regression Model Accuracy, Precision, and Recall scores.

Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances.

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384



## Summary

The logistic regression model is doing a very good job predicting the healthy loans (class 0), with precision 1.00, recall 0.99. For the risky loans (class 1), the model is still ok, precision 0.84 and recall 0.94.




