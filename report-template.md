# Module 12 Report Template

## Overview of the Analysis

The main reason for this analysis is to evaluate the performance and process of machine learning models, specifically logistic regression models, in predicting credit risk. The analysis aims to assess the ability of these models to differentiate between healthy loans (0) and high-risk loans (1) based on financial information.

The data used in this analysis contains information about lending activities, including various financial variables such as loan amount, interest rate, annual income, debt-to-income ratio, loan dates and loan status. The variable of interest is the "loan_status" column, which indicates whether a loan is classified as healthy (0) or high-risk (1). The information used for the study and analysis it is based on a day to day scenario.

To initate the project, the dataset needs to be loaded into Pandas. The labels (y) were extracted from the "loan_status" column, while the remaining columns were used as features (X). The balance of the labels variable was checked using the value_counts function to understand the distribution of healthy loans and high-risk loans.

The analysis is mostly based of:

Logistic Regression with Original Data:

The original data was split into training and testing datasets using the train_test_split function.
A logistic regression model was fitted using the training data.
Predictions were made on the testing data using the fitted model.
The model's performance was evaluated by calculating the accuracy score, generating a confusion matrix, and printing the classification report.

Logistic Regression with Resampled Data:

To address the imbalance in the dataset, the RandomOverSampler module from the imbalanced-learn library was used to resample the data.
The logistic regression model was fitted using the resampled training data.
Predictions were made on the testing data using the fitted model.
The model's performance was evaluated by calculating the accuracy score, generating a confusion matrix, and printing the classification report.
The logistic regression models were implemented using the LogisticRegression class from scikit-learn. The original data was used in the first model, while the resampled data was used in the second model to mitigate the issue of class imbalance.

Through the analysis, the focus is mostly assessing the model's ability to predict one the healthy loans (0) and high-risk loans (1) accurately. This was evaluated using metrics such as accuracy, precision, recall, and the balanced accuracy score.

## Results

Machine Learning Model 1:

Balanced Accuracy Score:  0.9928424039205571
Precision Score: .88
Recall Score: .91


Machine Learning Model 2:

Balanced Accuracy Score: 0.9952282692803714
Precision Score: .87
Recall Score: 1.0

## Summary

Considering the performance measures of both models, it can be observed that both models achieved high precision scores and relatively high precision and recall scores. However, Model 2 outperformed Model 1 in  balanced precision and recall scores. 

 The choice of  model depends on the problem we are trying to solve. If accurate prediction of subprime loans (label 1) is more important, model 2 is recommended because it has the perfect recovery point in label 1. On the other hand, if there is a good balance between precision and recall for both labels, Model 1 could be a suitable choice.  Ultimately, the choice of  model should be based on the specific requirements and priorities of the problem at hand. It is recommended to consider the consequences and costs of false positives and false negatives in order to make an informed decision.
