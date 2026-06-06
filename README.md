# codeAlpha_heart_disease_prediction
# Heart Disease Prediction Using Machine Learning

## Overview

This project predicts the likelihood of heart disease using machine learning algorithms and clinical patient data. The dataset includes demographic information, symptoms, vital signs, and blood test results. Multiple classification models were trained and evaluated to identify the best-performing algorithm.

## Features

* Data preprocessing and feature engineering
* Label encoding for categorical variables
* Train-test data splitting
* Feature scaling using StandardScaler
* Model comparison using:

  * Logistic Regression
  * XGBoost Classifier
  * Random Forest Classifier
  * Decision Tree Classifier
* Feature importance analysis

## Dataset Features

* Age
* Gender
* Chest Pain
* Blood Pressure
* Blood Glucose
* Cholesterol
* Triglycerides
* Troponin
* BNP
* CRP
* Creatinine
* CK-MB
* Other clinical indicators

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 99%      |
| XGBoost             | 98%      |
| Random Forest       | 97.5%    |
| Decision Tree       | 88%      |

## Top Important Features

1. BNP
2. CRP
3. Creatinine
4. Troponin
5. Age
6. CK-MB
7. Chest Pain
8. Arm/Jaw Pain
9. Blood Glucose
10. Triglycerides

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Feature Encoding
4. Train-Test Split
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis

## Conclusion

The project demonstrates that machine learning models can effectively predict heart disease using clinical and blood-test biomarkers. Logistic Regression achieved the highest accuracy of 99%, while XGBoost and Random Forest also produced excellent results.
