# Credit Card Default Prediction Model

## 1. Project Overview

This project focuses on predicting whether a customer is likely to default on their credit obligations using Machine Learning techniques. A Logistic Regression model is developed to analyze customer financial information and identify patterns associated with credit default.

The project uses Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, and Scikit-learn for data analysis, visualization, model development, and evaluation.

## 2. Objective

The main objective of this project is to develop a Machine Learning classification model that predicts whether a customer will default on their credit payments based on their financial and personal information.

The model aims to:
- Analyze customer financial and credit-related information.
- Identify important factors associated with credit default.
- Predict whether a customer is likely to default (1) or not default (0).
- Evaluate model performance using classification metrics.
- Understand the relationship between customer characteristics and credit default risk.

## 3. Dataset Description

The dataset contains 400 customer records and 8 columns.

The features include:

| Feature | Description |
|---|---|
| age | Customer's age |
| annual_income | Customer's annual income |
| credit_score | Customer's credit score |
| loan_amount | Amount of loan |
| dti | Debt-to-income ratio |
| missed_payments | Number of missed payments |
| employment_type | Customer's employment category |
| default | Target variable (0 = No Default, 1 = Default) |

## 4. Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- Joblib

## 5. Methodology

The following steps were performed:

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Categorical Variable Encoding using Dummy Variables
4. Feature Selection
5. Splitting Data into Training and Testing Sets (80:20)
6. Building a Logistic Regression Model
7. Statistical Significance Analysis
8. Model Prediction
9. Model Evaluation

## 6. Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised Machine Learning classification algorithm used to predict the probability of a binary outcome.

In this project:
- 0 represents No Default.
- 1 represents Default.

The model analyzes customer information to estimate the probability of credit default.

## 7. Model Evaluation

The model is evaluated using the following techniques:

- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- ROC Curve

These evaluation techniques help assess how effectively the model distinguishes between customers who default and those who do not.

## 8. Model Deployment / Saving

The trained Logistic Regression model is saved using Joblib in a file named `model.pkl` for future use.

## 9. Project Files

- `Project_logistic_Regression.ipynb` – Jupyter Notebook containing data analysis, model development, predictions, and evaluation.
- `credit_data - 1782056531013.csv` – Dataset used for model training and testing.
- `model.pkl` – Saved trained model (generated when the notebook is executed).

## 10. Conclusion

This project demonstrates how Logistic Regression can be used to predict credit default using customer financial and credit-related information.

It also provides insights into the factors associated with credit default and demonstrates the application of Machine Learning in financial risk analysis.

## 11. Author

**Shiva Tiwari**
