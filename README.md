# Stroke Risk Prediction Using Machine Learning

## Overview
Stroke is a leading cause of death and long-term disability worldwide. Early identification of individuals at high risk is critical for prevention and timely intervention.  
This project uses real-world clinical data to analyze stroke risk factors and build predictive machine learning models to support population health and clinical decision-making.

## Objective
- Identify clinical and demographic factors associated with stroke occurrence
- Build and evaluate predictive models for stroke risk
- Address class imbalance commonly seen in healthcare datasets
- Emphasize clinically meaningful evaluation metrics such as recall and ROC-AUC

## Dataset
- Source: Kaggle Stroke Prediction Dataset
- Records: 5,100+ patient records
- Population: Adults aged 50–80
- Key features: Age, hypertension, heart disease, BMI, average glucose level, smoking status, residence type, and work type
- Target variable: Stroke occurrence (Yes / No)

## Methodology
- SQL and Python-based data cleaning (filtering, deduplication, missing values)
- Exploratory Data Analysis (EDA)
- Statistical testing (t-tests, chi-square, normality tests)
- Feature engineering and encoding
- Train-test split with stratification
- SMOTE oversampling applied to training data only
- Model development using Logistic Regression and Random Forest
- Model evaluation using confusion matrices, ROC curves, precision, and recall

## Key Results
- Age, average glucose level, hypertension, and heart disease were the strongest predictors of stroke
- Logistic Regression achieved moderate performance with ROC-AUC ≈ 0.70 and better recall for stroke cases
- Random Forest achieved high accuracy but performed poorly in detecting stroke cases due to class imbalance
- Results highlight the importance of recall and sensitivity in clinical prediction models

## Tools & Technologies
- Python (Pandas, NumPy, scikit-learn, Matplotlib)
- SQL
- Jupyter Notebook
- SMOTE (imbalanced-learn)
- Power BI / Tableau (visual analysis)

## Repository Structure
