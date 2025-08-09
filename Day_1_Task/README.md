# 🚢 Task 1: Data Cleaning & Preprocessing 🛳

![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Dataset](https://img.shields.io/badge/Dataset-Titanic-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📜 Table of Contents
- [📖 About](#-about)
- [✅ Task Checklist](#-task-checklist)
- [⚙ Steps](#%EF%B8%8F-steps)
- [📂 Code Structure](#-code-structure)
- [📁 Deliverables](#-deliverables)
- [▶ How to Use](#%EF%B8%8F-how-to-use)
- [👤 Author](#-author)
- [🏆 GitHub Achievements](#-github-achievements)

---

## 📖 About
<details>
<summary>Click to expand</summary>

This project focuses on *full data cleaning and preprocessing* on the *Titanic dataset* 🛳.  
The goal is to prepare the dataset for machine learning by handling missing values, encoding categorical variables, scaling numerical features, and removing outliers.  
Visualizations are also included to better understand the data distribution.

</details>

---

## ✅ Task Checklist

- [x] *🔍 Import and Explore Data*
- [x] *🧹 Handle Missing Values*
- [x] *🔢 Encode Categorical Features*
- [x] *⚖ Normalize/Standardize Numerical Data*
- [x] *🚫 Detect and Remove Outliers*
- [x] *📊 Visualize Distributions and Outliers*

---

## ⚙ Steps

### 1. Import and Explore
- Loaded dataset from [Titanic CSV](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)
- Checked data types, shape, and null values with .info() and .isnull().sum()

### 2. Handle Missing Values
- Filled Age column missing values with median 🧮

### 3. Encode Categorical Variables
- Converted Sex to numeric: *0* for male, *1* for female 👨‍👩‍👧

### 4. Normalize/Standardize
- Standardized Age and Fare using *z-score* formula 📏

### 5. Outlier Detection & Removal
- Created *boxplots* for Age and Fare
- Removed outliers using *Interquartile Range (IQR)* method

### 6. Visualizations
- Saved boxplots as boxplots.png 🖼

---

## 📂 Code Structure
```bash
Task1/
│── task1_data_cleaning.ipynb   # Jupyter notebook with full workflow
│── cleaned_titanic.csv         # Final cleaned dataset
│── boxplots.png                # Outlier visualizations
│── README.md                   # This enhanced documentation
