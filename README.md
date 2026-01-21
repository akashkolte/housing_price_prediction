# 🏠 Housing Price Prediction

A machine learning project that predicts house prices using the **House Prices: Advanced Regression Techniques** dataset from Kaggle.

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

The dataset used comes from the **Kaggle House Prices competition**:

- `train.csv` → training data with labels  
- `test.csv` → data to make predictions on  

You must download these files from Kaggle and place them in the same project directory.

Dataset link:  
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

---

## 🛠 Key Steps in the Notebook

### 🔍 1. Exploratory Data Analysis (EDA)
- Understand target variable distribution
- Handle right skew using log transformation
- Identify relationships between features and target

### 📊 2. Data Cleaning & Preprocessing
- Handle missing values
- Apply transformations
- Encode categorical features
  - One-Hot Encoding for nominal categories
  - Custom ordering / label encoding for ordinal relationships

### 🤖 3. Model Training
Two models were trained and evaluated:
- **Linear Regression**  
- **XGBoost Regressor**

XGBoost achieved significantly better performance.

### 🔎 4. Model Evaluation
Used metrics like:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

---

## 📈 Results Summary

| Model              | R² Score |
|-------------------|----------|
| Linear Regression | ~0.80     |
| XGBoost Regressor | ~0.91     |

XGBoost performed much better due to its ability to handle nonlinear relationships and complex interactions.

---

## 📦 How to Run

1. Clone repository  
   ```bash
   git clone https://github.com/akashkolte/housing_price_prediction.git
2.	Download dataset files from Kaggle
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
