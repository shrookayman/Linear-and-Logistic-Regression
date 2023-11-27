# Linear and Logistic Regression

## Overview

This Python program demonstrates the application of linear and logistic regression on a dataset. The steps include loading the dataset, performing analysis, preprocessing the data, fitting regression models, and evaluating their performance.

## Dataset

- **Name:** "loan_old.csv"

## Analysis

a) Load the dataset and perform analysis:

i) Check for missing values
ii) Identify the type of each feature (categorical or numerical)
iii) Check whether numerical features have the same scale
iv) Visualize a pairplot between numerical columns

## Data Preprocessing

c) Preprocess the data:

i) Remove records with missing values
ii) Separate features and targets
iii) Shuffle and split data into training and testing sets
iv) Encode categorical features
v) Encode categorical targets
vi) Standardize numerical features

## Linear Regression

d) Fit a linear regression model to predict loan amount using sklearn's linear regression.

e) Evaluate the linear regression model using sklearn's R² score.

## Logistic Regression

f) Fit a logistic regression model to predict loan status:

- Implement logistic regression from scratch using gradient descent.

g) Write a function (from scratch) to calculate the accuracy of the model.

## Additional Dataset

h) Load the "loan_new.csv" dataset.

i) Perform the same preprocessing steps (excluding shuffling and splitting).

## Model Application

j) Use the trained models on the new dataset to predict:

- Loan amounts
- Loan status




