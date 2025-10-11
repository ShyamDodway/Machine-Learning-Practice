# Machine Learning Algorithms Practice
<p align="center">
  <b><span style="color:red;">⚠️ Disclaimer / Note:</span></b><br>
  These are my <b>practice implementations</b> of various <b>machine learning algorithms</b>.<br>
  The main goal of this repository is <i>learning, experimentation, and improvement</i>.<br>
  Models may not be fully optimized or produce high accuracy — they’re for <b>educational purposes only</b>. 
</p>

##  Contents
# 1.Linear Regression 
#### https://github.com/ShyamDodway/ml-algorithms-practice/blob/main/linear_regression.ipynb

- A real state agents want the help to predict the house price for regions in the USA. He gave the dataset to work on and i  decided to use Linear Regressioon Model. Create a model which will help him to estimate of what the house would sell for.

Dataset contains 7 columns and 5000 rows with CSV extension. The data contains the following columns :

- 'Avg. Area Income': Avg. Income of householder of the city house is located in.
- 'Avg. Area House Age': Avg. Age of Houses in same city.
- 'Avg. Area Number of Rooms': Avg. Number of Rooms for Houses in same city.
- 'Avg. Area Number of Bedrooms': Avg. Number of Bedrooms for Houses in same city.
- 'Area Population': Population of city.
- 'Price': Price that the house sold at.
- 'Address': Address of the houses.

# 2. Logistic Regression
#### https://github.com/ShyamDodway/ml-algorithms-practice/blob/main/Logistic_Regression.ipynb
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

# 3.KNN 
#### https://github.com/ShyamDodway/ml-algorithms-practice/blob/main/KNN.ipynb
KNN Classifier Evaluation
This repository contains a K-Nearest Neighbors (KNN) classifier implemented using scikit-learn, along with comprehensive evaluation metrics (accuracy, precision, recall, confusion matrix, and classification report).​

Features:
- Loads and splits dataset
- Trains a KNN classifier
- Evaluates model with multiple metrics
- Easy to modify for your own data

## Model Evaluation Results

**Accuracy:** 0.6688  
**Precision:** 0.6622  
**Recall:** 0.6688  

### Confusion Matrix
|        | Predicted 0 | Predicted 1 |
|--------|-------------|-------------|
| Actual 0 |   77        |   23        |
| Actual 1 |   28        |   26        |

### Classification Report
| Class | Precision | Recall | F1-score | Support |
|-------|-----------|--------|----------|---------|
| 0     |   0.73    |  0.77  |   0.75   |   100   |
| 1     |   0.53    |  0.48  |   0.50   |    54   |
|**Accuracy**|        |        |  0.67    |   154   |
| Macro avg | 0.63   |  0.63  |   0.63   |   154   |
| Weighted avg | 0.66|  0.67  |   0.66   |   154   |
