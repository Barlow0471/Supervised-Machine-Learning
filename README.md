# Supervised Machine  Learning

In this assignment, you will be building a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not.

## Background
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.

## Instructions

Retrieve the data
In the Generator folder in Resources, there is a GenerateData.ipynb notebook that will download data from LendingClub and output two CSVs: 2019loans.csv, 2020Q1loans.csv

You will be using an entire year's worth of data (2019) to predict the credit risk of loans from the first quarter of the next year (2020).
Note: these two CSVs have been undersampled to give an even number of high risk and low risk loans. In the original dataset, only 2.2% of loans are categorized as high risk. To get a truly accurate model, special techniques need to be used on imbalanced data. Undersampling is one of those techniques. Oversampling and SMOTE (Synthetic Minority Over-sampling Technique) are other techniques that are also used.

## Findings and Predictions
I predicted that the Random Forest Classifier model would be more accurate. The test data score of the Random Forest Classifier was more accurate with a score of .64 while the Logisitc Regression model had a test data score of .52. 

The scaled data scores were very surprising to me as the Logistic Regression model had training and testing scores of .71 and .77 respectively. While the Random Forest Classifier model had training and testing scores of 1.0 and .64.
