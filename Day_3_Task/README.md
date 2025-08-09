# 🏠 Task 3: Linear Regression – Boston Housing Price Prediction

**Author:** Joy Biswas  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)  
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.0%2B-orange?logo=scikit-learn)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![License](https://img.shields.io/badge/License-MIT-yellow)  

---

## 📋 Overview

This project demonstrates **Multiple Linear Regression** to predict the median value of owner-occupied homes in Boston using the **Boston Housing dataset**.  

We build, train, and evaluate a regression model to explore how different features (like crime rate, number of rooms, and property tax rate) affect housing prices. The project also includes data preprocessing, performance evaluation, and visualization for better interpretability.

---

## 📊 Dataset Information

- **Source:** Boston Housing dataset (from `sklearn.datasets`)
- **Number of Instances:** 506  
- **Number of Features:** 13 (e.g., CRIM, RM, TAX, LSTAT)  
- **Target Variable:** MEDV (Median value of homes in $1000s)  
- **Type:** Numerical regression dataset  

---

## ✅ Steps Performed

1. **Data Loading & Exploration**
   - Loaded dataset from `scikit-learn`
   - Displayed dataset statistics and feature details

2. **Data Preprocessing**
   - Checked for null values and anomalies
   - Converted to a pandas DataFrame for analysis

3. **Model Development**
   - Split data into **80% training** and **20% testing**
   - Trained a `LinearRegression()` model using `scikit-learn`

4. **Model Evaluation**
   - Metrics used:  
     - Mean Absolute Error (**MAE**)  
     - Mean Squared Error (**MSE**)  
     - R² Score (**R2**)
   - Interpreted regression coefficients to understand feature importance

5. **Visualization**
   - Scatter plot comparing **Actual vs Predicted Prices**
   - Regression line overlay for visual fit assessment

6. **Saving Results**
   - Exported cleaned dataset as `cleaned_boston_housing.csv`
   - Saved plots in `screenshots/` directory

---

## 📁 Files Included

- `task3_linear_regression.ipynb` → Jupyter Notebook with full implementation  
- `cleaned_boston_housing.csv` → Cleaned dataset ready for modeling  
- `screenshots/actual_vs_predicted.png` → Scatter plot of predictions  

---

## 📈 Sample Results

| Metric         | Value   |
|----------------|---------|
| MAE            | 3.42    |
| MSE            | 21.51   |
| R² Score       | 0.74    |

*(Values are from sample run — may vary depending on random seed and environment)*

---

## ▶️ How to Run

**1️⃣ Clone Repository**
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
