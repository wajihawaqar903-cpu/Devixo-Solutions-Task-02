# Devixo-Solutions-Task-02
customer churn prediction using Python
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
## Conclusion

In this project, I developed and compared machine learning models to predict customer churn using Python and Scikit-learn. I trained Logistic Regression, Decision Tree, and Random Forest models and used RandomizedSearchCV to tune the Random Forest model.

The tuned Random Forest achieved **97.53% accuracy, 42.70% precision, 56.52% recall, 48.65% F1-score, and 95.93% ROC-AUC** on the test set. These results show that the model can identify many customers who may churn, although further improvement is needed to reduce missed churn cases and false-positive predictions.

Feature-importance analysis identified `tenure_months` as the most influential feature, followed by `monthly_usage_hours`.

This project strengthened my practical understanding of data preparation, machine learning, model evaluation, hyperparameter tuning, and feature importance. Future improvements could include class weighting and decision-threshold adjustment to improve churn detection.
