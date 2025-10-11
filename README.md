# Machine Learning Algorithms Practice

This repository contains my personal implementations and practice notebooks for various ML algorithms.
##  Contents
# 1.Linear Regression 

- A real state agents want the help to predict the house price for regions in the USA. He gave the dataset to work on and i  decided to use Linear Regressioon Model. Create a model which will help him to estimate of what the house would sell for.

Dataset contains 7 columns and 5000 rows with CSV extension. The data contains the following columns :

- 'Avg. Area Income': Avg. Income of householder of the city house is located in.
- 'Avg. Area House Age': Avg. Age of Houses in same city.
- 'Avg. Area Number of Rooms': Avg. Number of Rooms for Houses in same city.
- 'Avg. Area Number of Bedrooms': Avg. Number of Bedrooms for Houses in same city.
- 'Area Population': Population of city.
- 'Price': Price that the house sold at.
- 'Address': Address of the houses.

# 2. Logistic Regression (https://github.com/ShyamDodway/ml-algorithms-practice/blob/main/Logistic_Regression.ipynb)
This project demonstrates the implementation of Logistic Regression, a supervised machine learning algorithm used for binary classification problems. The goal is to predict the outcome (class 0 or 1) based on input features and the about the dataset i mention with code file section.
Steps Followed

Data Exploration – Checked dataset shape, missing values, and basic statistics.

Preprocessing – Feature scaling (Z-score normalization), handling nulls if any.

Train-Test Split – Split dataset into training and testing sets.

Model Training – Trained logistic regression on training data.

Evaluation Metrics – Calculated:

Accuracy: 0.9835

ROC-AUC Score  : 0.8106

Classification Report:
               precision    recall  f1-score   support

           0       0.99      1.00      0.99       824
           1       0.86      0.50      0.63        24

    accuracy                           0.98       848
   macro avg       0.92      0.75      0.81       848
weighted avg       0.98      0.98      0.98       848
