# 🚢 Task 1: Data Cleaning & Preprocessing – Titanic Dataset

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-%23150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Matrix%20Math-lightblue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal)
![Dataset](https://img.shields.io/badge/Dataset-Titanic-green)

---

## 📑 Table of Contents
- [📖 Overview](#-overview)
- [✅ Task Checklist](#-task-checklist)
- [🛠 Steps](#-steps)
- [📂 Deliverables](#-deliverables)
- [▶ How to Use](#-how-to-use)
- [🏆 Author & GitHub Stats](#-author--github-stats)

---

## 📖 Overview
This project covers *full data cleaning and preprocessing* on the *Titanic dataset* 🛳, preparing it for downstream analysis and machine learning modeling.

---

## ✅ Task Checklist
- 🔍 Import & Explore Data  
- 🧹 Handle Missing Values  
- 🔢 Encode Categorical Features  
- ⚖ Normalize/Standardize Numerical Data  
- 🚫 Detect & Remove Outliers  
- 📊 Visualize Data Distributions  

---

<details>
<summary>🛠 <b>Steps</b></summary>

### 1️⃣ Import & Explore  
```python
import pandas as pd
df = pd.read_csv("titanic.csv")
df.info()
df.isnull().sum()
