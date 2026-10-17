# Devixo-Solutions-Task-02
Laptop Dataset Analysis using Python
# Devixo Solutions Task 02: Customer Churn Prediction

## Project Overview
This project uses machine learning to predict customer churn and compare model performance.

## Dataset
- 50,000 customer records
- Six input features
- Target column: `churn`
- No missing values or duplicate rows were found during initial inspection.

## Machine Learning Models
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Tuned Random Forest

## Evaluation Metrics
Accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

## Hyperparameter Tuning
RandomizedSearchCV with cross-validation was used to tune the Random Forest model.

## Feature Importance
The most influential features in the tuned Random Forest were tenure months and monthly usage hours.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
