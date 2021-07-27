# Home-Loan-Prediction
This project demonstrates how a Housing Finance company, among all their customers will choose their valuable customers who are eligible to get home loans for the houses which were present across all urban, semi-urban and rural areas.

# Project Overview

In this project, we will be using one training data file (csv) to train our prediction model and then apply the model on Test data file

### DataSet Description

The training Dataset is having 615 rows and 13 features
The test Dataset is having 367 rows and 12 features

### Importing all the necessary libraries

All the below libraries have been used in this project

1. pandas
2. numpy
3. sklearn.metrics
4. sklearn.model_selection
5. sklearn.preprocessing
6. matplotlib
7. seaborn

### Understand the Data set

1. check the data types of the different features
2. Remove all the null values from the dataset
3. Remove all the duplicate values
4. Identify the dependent and independent features

### Exploratory Data Analysis

1. Univariate Analysis
2. Bivariate Analysis

### Preprocessing of the Data

1. Handling all the missing values in the dataset
2. Handle all the outliers in the data
3. Handle all the categorical features
4. Normalization of the data

### Model Creation

The following models have been applied on the training data:

1. Logistic Regression
2. Support Vector Classifier
3. Decision Tree Classifier
4. Random Forest Classifier
5. Xgboost Classifier

Based on the output of the different models it is observed that the SVM classifier is providing the best result, so this SVM classifier has been applied to the test dataset as well.


