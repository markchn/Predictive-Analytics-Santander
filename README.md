# Santander-Prediction

## Background
Santander Bank is a retail banking group based in Boston and mainly focusing on the northeastern U.S. market. It diversifies itself by making use of data and running predictive analytics based on data to generate insights. In this specific problem, given certain features about a group of customers, we attempt to predict whether a customer will do a certain transaction or not.

## Data Acquisation and Description
All of the data used in the following analysis can be found through this link as part of a now closed Kaggle contest: 
https://www.kaggle.com/c/santander-customer-transaction-prediction

We are provided with two files, train.csv and test.csv. Both training and testing data have 200k samples each. 

train.csv- contains training data, 202 columns total including features, ID, and target
test.csv- contains testing data, 201 columns total including features, ID

Each of the 200 features are anonymized numerical columns identified with a unique arbitrary number. Our goal is to fit models based on the provided data and features and choose the best one that minimizes overfitting while preserving the meaning of the features provided and predict if a customer will perform a certain transaction or not.

## Software & Tools
The coding software used in this project is Python 3.7, and feature engineering, selection and model training and comparison were all performed on Google Colab. In particular, the following packages were used:

Preliminary data processing & Visualization
- pandas
- numpy
- seaborn

Feature engineering & Model selection
- sklearn

## File Guideline
