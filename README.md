# telecom-churn-prediction-py

# Telecom Customer Churn Prediction

## Overview
This project aims to develop and compare machine learning models for predicting customer churn in a telecommunication company.

## Goals
1. **Develop Machine Learning Models**: Build and train machine learning models to predict customer churn.
2. **Compare Model Performance**: Evaluate and compare the performance of different machine learning models on the customer churn prediction task.
3. **Feature Selection**: Identify the most relevant features for customer churn prediction through various feature selection techniques.

## Methodology
Machine learning techniques were employed to analyze customer data and predict churn.

## Data
The project utilized customer data including:
- Demographics (e.g., Gender, Age)
- Customer accounts (e.g., Tenure in Months, Offer, Contract)
- Service information (e.g., Phone and Internet services)

The target variable is "Customer Status," indicating churn, retention, or acquisition.

## Key Findings
- **Consistent Features**: A comprehensive feature selection process was implemented using correlation matrix, ANOVA (Analysis of Variance), backward elimination, and recursive feature elimination (RFE) techniques. Seven features emerged as consistently important across all selection methods, suggesting their significant influence on churn prediction.
- **Model Performance**: The Random Forest model demonstrated the best overall performance, particularly when trained on imbalanced data (typical of customer churn datasets) using all available features. It maintained high accuracy across different feature sets selected using RFE and ANOVA, highlighting its robustness and adaptability.

Overall, the project indicates that the Random Forest model effectively tackles the challenge of customer churn prediction in the telecom industry, especially considering its performance on imbalanced data. Further exploration of other machine learning techniques or hyperparameter tuning could be considered for future enhancements.

## Folder Structure
- Main folder: telecom-churn-prediction-py
- Files: script, images

## Dependencies
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Plotly.express
- Scipy
- Scikit-learn
- Joblib
- Streamlit
