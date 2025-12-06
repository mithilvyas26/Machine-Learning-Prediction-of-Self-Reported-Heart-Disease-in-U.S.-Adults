# Heart Disease Prediction – EDA, Risk Factors, and Model Comparison

This repository contains the code and analysis for our study on the **Indicators of Heart Disease (2022 UPDATE)** dataset.

## Overview
The analysis in `final_code.ipynb` performs the following:
1.  **Exploratory Data Analysis (EDA)** of key heart disease indicators.
2.  **Hypothesis Testing:**
    * *H1:* Assessing the association of risk factors (Age, BMI, Smoking, etc.) with heart disease.
    * *H2:* Comparing non-linear ML models (Random Forest, XGBoost) against Logistic Regression.
3.  **Model Development:** Building and tuning models using stratified cross-validation.
4.  **Explainability:** Using SHAP values and feature importance to interpret model predictions.

## Installation
To run this notebook locally, install the required dependencies:

```bash
pip install -r requirements.txt