<!-- Elegant Header -->
<h1 align="center">🚢 Task 1: Data Cleaning & Preprocessing 🛳</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Status-✅%20Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/badge/Dataset-Titanic-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## 📜 Table of Contents
- [📖 About](#-about)
- [✅ Task Checklist](#-task-checklist)
- [⚙ Steps](#-steps)
- [📂 Code Structure](#-code-structure)
- [📁 Deliverables](#-deliverables)
- [▶ How to Use](#-how-to-use)
- [👤 Author](#-author)
- [🏆 GitHub Achievements](#-github-achievements)

---

## 📖 About
<details>
<summary><b>🔍 Click to expand</b></summary>

This project focuses on **full data cleaning and preprocessing** for the **Titanic dataset** 🛳.  
The main objective is to prepare the dataset for machine learning by:
- Handling missing values  
- Encoding categorical variables  
- Scaling numerical features  
- Removing outliers  
- Creating insightful visualizations  

The final output is a **clean, analysis-ready dataset** along with visualizations for better understanding.

</details>

---

## ✅ Task Checklist
| Status | Task |
|--------|------|
| ✔ | 🔍 Import and Explore Data |
| ✔ | 🧹 Handle Missing Values |
| ✔ | 🔢 Encode Categorical Features |
| ✔ | ⚖ Normalize/Standardize Numerical Data |
| ✔ | 🚫 Detect and Remove Outliers |
| ✔ | 📊 Visualize Distributions and Outliers |

---

## ⚙ Steps

### **1️⃣ Import & Explore**
- Loaded dataset from [Titanic CSV](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)  
- Checked data types, shape, and null values using `.info()` and `.isnull().sum()`  

### **2️⃣ Handle Missing Values**
- Filled `Age` column missing values with **median** 🧮  

### **3️⃣ Encode Categorical Variables**
- Converted `Sex` to numeric: **0 = Male**, **1 = Female** 👨‍👩‍👧  

### **4️⃣ Normalize/Standardize**
- Applied **Z-score** standardization to `Age` and `Fare` 📏  

### **5️⃣ Outlier Detection & Removal**
- Created **boxplots** for Age and Fare  
- Removed outliers using **Interquartile Range (IQR)** method  

### **6️⃣ Visualizations**
- Saved all boxplots as **`boxplots.png`** 🖼  

---

## 📂 Code Structure
```bash
Task1/
│── task1_data_cleaning.ipynb   # Full workflow in Jupyter Notebook
│── cleaned_titanic.csv         # Final cleaned dataset
│── boxplots.png                # Outlier visualizations
│── README.md                   # Documentation for Task 1
