# 🏠 Housing Price Prediction

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Regression-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A machine learning project that predicts house prices using the  
**House Prices: Advanced Regression Techniques** dataset from Kaggle.

This notebook implements an end-to-end regression pipeline — from data exploration and preprocessing to training and evaluating models like **Linear Regression** and **XGBoost**.

---

## 📌 Problem Description

Given various features of a house (like size, location, year built, and more), the goal is to build a model that can accurately predict its **sale price**.

This project focuses on:

✔ Exploratory Data Analysis (EDA)  
✔ Handling missing values & transformations  
✔ Categorical encoding  
✔ Model training and evaluation  
✔ Performance comparison  

---

## 📁 Dataset

Dataset: **Kaggle – House Prices: Advanced Regression Techniques**

Files used:
- `train.csv` → training data with labels  
- `test.csv` → data to make predictions on  

Download from:  
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

---

## 🛠 Key Steps in the Notebook

### 🔍 1. Exploratory Data Analysis
- Analyzed SalePrice distribution  
- Handled right skew using log transformation  
- Correlation analysis of top features  

### 📊 2. Data Cleaning & Preprocessing
- Missing value handling  
- Feature engineering  
- Encoding:
  - One-Hot Encoding for nominal features  
  - Label Encoding for ordinal features  

### 🤖 3. Model Training
Models used:
- Linear Regression  
- XGBoost Regressor  

### 🔎 4. Model Evaluation
Metrics:
- RMSE  
- MAE  
- R² Score  

---

## 📈 Results Summary

| Model              | R² Score |
|-------------------|----------|
| Linear Regression | ~0.80     |
| XGBoost Regressor | ~0.91     |

XGBoost performed significantly better due to its ability to capture non-linear relationships.

---

## 📦 How to Run

git clone https://github.com/akashkolte/housing_price_prediction.git

1.	Download dataset files from Kaggle
3.	Place train.csv and test.csv in the project directory
4.	Open and run the notebook or use Google Colab


📌 Notes

✔ No API keys or secrets are included
✔ Outputs have been cleared for clarity
✔ Focus on reproducibility and best practices


❤️ Author

Akash Kolte
	•	MS in Computer Science (AI/ML) — SUNY Buffalo
	•	GitHub: https://github.com/akashkolte
	•	LinkedIn: https://linkedin.com/in/akash-kolte

🚀 What You Can Improve
	•	Hyperparameter tuning (Grid Search / Random Search)
	•	Feature selection using feature importance
	•	Visualization of model predictions vs actuals
	•	Deployment as a web app (Streamlit / FastAPI)
