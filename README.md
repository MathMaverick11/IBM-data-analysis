IBM HR Attrition Analysis

This project performs an end-to-end analysis of the IBM HR Analytics dataset to understand factors affecting employee attrition and build a predictive model.

Project Overview

Objective: Analyze HR data to identify patterns in employee attrition and build a model to predict whether an employee is likely to leave.

Dataset: IBM HR Analytics dataset with 33 features including employee demographics, job role, satisfaction, and work-related metrics.

Key Steps

Data Preprocessing:

Cleaned and formatted data, handled missing values, mapped categorical variables, and removed identifiers.

Exploratory Data Analysis (EDA):

Visualized feature distributions, target relationships, and key patterns (e.g., attrition vs. department, distance from home, business travel).

Model Building:

Implemented Logistic Regression with StandardScaler and hyperparameter tuning using GridSearchCV.

Evaluated model performance using accuracy, ROC AUC, confusion matrix, and classification report.

Results:

Achieved 87.07% test accuracy and ROC AUC = 0.8156, demonstrating the model’s effectiveness in predicting employee attrition.

Tools & Technologies

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn

Insights

Employees in certain departments or with high travel frequency are more likely to leave.

Model helps HR teams proactively identify at-risk employees and make data-driven decisions to reduce attrition.
