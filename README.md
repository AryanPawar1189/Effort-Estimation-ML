# Effort Estimation Using Machine Learning

## Overview

This project develops a machine learning-based effort estimation system to predict project effort using historical estimation records. Accurate effort estimation is critical for project planning, resource allocation, budgeting, and delivery forecasting.

The solution leverages supervised machine learning techniques to identify patterns in historical project data and generate effort predictions for new projects. Multiple regression models were evaluated, including Random Forest Regressor and XGBoost Regressor, with extensive preprocessing, feature engineering, hyperparameter tuning, and cross-validation.

---

## Problem Statement

Traditional effort estimation often relies on expert judgment and manual calculations, which can be subjective and inconsistent. The objective of this project is to build a data-driven model capable of predicting project effort using historical estimation attributes.

The system aims to:

* Improve estimation accuracy
* Reduce manual effort in project planning
* Support data-driven decision making
* Identify key factors influencing project effort

---

## Features

* Data preprocessing and cleaning
* Categorical feature encoding using Label Encoding
* Correlation analysis and feature selection
* Random Forest based effort prediction
* XGBoost based effort prediction
* Hyperparameter tuning using GridSearchCV
* K-Fold Cross Validation
* Model evaluation using MAE, MSE, and R² metrics
* Feature importance analysis
* Visualization of model performance

---

## Machine Learning Pipeline

1. Data Collection
2. Data Cleaning
3. Feature Encoding
4. Exploratory Data Analysis
5. Correlation Analysis
6. Model Training
7. Hyperparameter Optimization
8. Cross Validation
9. Performance Evaluation
10. Prediction Generation

---

## Models Used

### Random Forest Regressor

Used as a baseline ensemble learning model to capture non-linear relationships within project estimation data.

### XGBoost Regressor

Gradient boosting-based model used to improve predictive accuracy and generalization performance.

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
* K-Fold Cross Validation Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn
* Google Colab

---

## Business Impact

The solution helps organizations:

* Improve project planning accuracy
* Reduce estimation uncertainty
* Optimize resource allocation
* Support project managers with data-driven forecasts
* Improve delivery predictability

---

## Future Improvements

* Deep Learning-based effort estimation
* Automated feature engineering
* Real-time prediction API using FastAPI
* MLOps deployment pipeline
* Explainable AI dashboards using SHAP

---

## Author

Aryan Pawar

BITS Pilani – M.Sc. Mathematics + Computer Science
