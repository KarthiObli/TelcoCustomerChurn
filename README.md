# Telco Customer Churn Prediction

## Overview

This project predicts customer churn for a telecom company using Machine Learning. The primary objective is to compare multiple classification models, identify the best-performing model, and determine the optimal probability threshold to achieve the desired balance between Precision and Recall.

## Project Highlights

- Performed Exploratory Data Analysis (EDA)
- Preprocessed data by handling missing values, skewness, and categorical features
- Balanced the dataset using **SMOTE**
- Trained and compared multiple machine learning models:
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Performed **RandomizedSearchCV** for hyperparameter tuning
- Compared model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Score
- Analyzed different probability thresholds using **Precision-Recall Trade-off** to identify the most suitable threshold based on business requirements.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Matplotlib
- Seaborn

## Goal

The final objective is to select the machine learning model and classification threshold that best predicts customer churn while minimizing false positives and false negatives according to business needs.

⭐ Feel free to explore the notebook and share your feedback!
