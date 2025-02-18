# Credit Card Fraud Detection

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Dataset](#2-dataset)
3. [Data Preprocessing](#3-data-preprocessing)
4. [Model training](#4-model-training)
5. [Model Evaluation](#5-model-evaluation)
6. [Results and Insights](#6-results)
7. [How to run the project](#7-how-to-run-the-project)
8. [Conclusion](#8-conclusion)

## 1. Project Overview

The Project aims to detect whether a Credit card transaction is Legit or Fraudulent using Machine Learning Techniques in Python.

## 2. Dataset 

Download the Dataset here : [Credit card](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code)
This Dataset contains:

- A large number of transactions with various features.

- As the credit card informations are highly sensitive the features are named as V1,V2...

- A highly unbalanced distribution of Legit vs. fraudulent transactions.
  

## 3. Data Preprocessing

- Loading the dataset using Pandas.

- Checking for missing values and handling them accordingly.

- As the dataset was highly unbalanced. To balance the ratio, the dataset was split into legit_transactions and fraud_transactions.

- Perform scaling and selection.

- Splitting the dataset into training and testing sets.


## 4. Model Training

- As the data can be classified into legit and fraud we will be using Logistic Regression as a baseline model.

- Other possible models that can be used: Decision Trees, Random Forest, and Neural Networks.

## 5. Model Evaluation

- The performance of the model is assessed using accuracy, precision, recall, and F1-score.
  

## 6. Results

- The model works perfectly as the training dataset accuracy score is not significantly larger or miniscule than the testing data set.
  
- The model does not have issue with underfitting or overfitting.


## 7. How to run the Project

1. Install the required dependencies using `pip install -r requirements.txt`.

2. Run the Jupyter Notebook step by step.

3. Evaluate the model’s performance and make necessary modifications.

## 8. Conclusion

This project demonstrates the effectiveness of machine learning techniques in detecting fraudulent transactions.
