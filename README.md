# Customer Churn Prediction and Analysis

## Introduction
We perform customer churn prediction on a bank customer dataset. The task is to predict whether a customer will exit the bank or not, based on his/her characteristics.

## Data
The dataset contains information on a bank's customers, including various features such as age, geography, gender, income, balance etc., as well as whether or not they exited the bank. [Source](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers)

## Stages
1. EDA
    - Plot distributions of customers based on various features such as age, geography, income etc.
    - Plot conditional distributions of these features for exiting/retained customers to derive insights
2. Preprocessing and Feature engineering
    - Convert categorical features to one-hot representation for classification
    - Split data into train and test sets for features and target
3. Logistic Regression Model
    - Training: Fit logistic regression model to train data and make predictions on test data
    - Evaluation: Plot confusion matrix and ROC curve and compute area under ROC curve
4. Decision Tree Model
    - Training: Fit decision tree model to train data and make predictions on test data
    - Plot decision tree for visualization of decision nodes
    - Evaluation: Plot confusion matrix and ROC curve and compute area under ROC curve
    - Causal inference: Analyze important features for trained model
5. Random Forest Model
    - Training: Fit random forest model to train data and make predictions on test data
    - Evaluation: Plot confusion matrix and ROC curve and compute area under ROC curve
    - Causal inference: Analyze important features for trained model
