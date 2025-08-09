# 🚢 Task 1: Data Cleaning & Preprocessing

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-%23150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-%23013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-%23ffffff?logo=plotly)

---

## 📜 Table of Contents
1. [📖 About the Project](#-about-the-project)
2. [✅ Task Checklist](#-task-checklist)
3. [⚙ Steps & Workflow](#-steps--workflow)
4. [📂 Deliverables](#-deliverables)
5. [▶ How to Use](#-how-to-use)
6. [🏆 Achievements](#-achievements)
7. [👤 Author](#-author)

---

## 📖 About the Project
<details>
<summary>Click to expand</summary>

This project covers *data cleaning and preprocessing* of the Titanic dataset 🛳, preparing it for further analysis or modeling.  
The steps include handling missing values, encoding categorical variables, scaling features, detecting/removing outliers, and visualizing data distributions.

Dataset: [Titanic CSV](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)
</details>

---

## ✅ Task Checklist

- [x] *🔍 Import and Explore Data*
- [x] *🧹 Handle Missing Values*
- [x] *🔢 Encode Categorical Features*
- [x] *⚖ Normalize/Standardize Numerical Data*
- [x] *🚫 Detect and Remove Outliers*
- [x] *📊 Create Visualizations*

---

## ⚙ Steps & Workflow

### 1️⃣ Import and Explore
- Load dataset from the provided link
- Inspect data types, shape, and null values using .info() and .isnull().sum()

### 2️⃣ Handle Missing Values
- Replace missing Age values with the median 🧮

### 3️⃣ Encode Categorical Variables
- Convert Sex → 0 (male), 1 (female) 👨‍👩‍👧

### 4️⃣ Normalize/Standardize
- Apply *z-score standardization* to Age & Fare 📏

### 5️⃣ Outlier Detection & Removal
- Create *boxplots* for Age & Fare to detect anomalies
- Remove outliers using *IQR method* 🚫

### 6️⃣ Visualizations
- Save boxplots in boxplots.png 🖼

---

## 📂 Deliverables
- **task1_data_cleaning.ipynb** → Full code & workflow  
- **cleaned_titanic.csv** → Final cleaned dataset  
- **boxplots.png** → Visualizations of Age & Fare distributions  
- **README.md** → This file  

---

## ▶ How to Use

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git

# Open Jupyter Notebook
jupyter notebook task1/task1_data_cleaning.ipynb
