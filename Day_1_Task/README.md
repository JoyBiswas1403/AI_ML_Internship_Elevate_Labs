# 🚢 Task 1: Data Cleaning & Preprocessing

This project covers full data cleaning and preprocessing on the Titanic dataset. 🛳️

---

## ✅ Task Checklist

1. **🔍 Import and Explore Data**
2. **🧹 Handle Missing Values**
3. **🔢 Encode Categorical Features**
4. **⚖️ Normalize/Standardize Numerical Data**
5. **🚫 Detect and Remove Outliers**

---

## 📝 Steps

### 1. Import and Explore
- Loaded Titanic dataset from [this link](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv)  
- Checked data types, dataset shape, and null values using `.info()` and `.isnull().sum()`

### 2. Handle Missing Values
- Filled missing values in the `Age` column with the median age of the dataset 🧮

### 3. Encoding Categorical Variables
- Converted the `Sex` column to numeric: 0 for male and 1 for female 👨‍👩‍👧

### 4. Normalization/Standardization
- Standardized `Age` and `Fare` features using z-score formula \((x - \text{mean}) / \text{std}\) 📏

### 5. Outlier Detection & Removal
- Created boxplots for `Age` and `Fare` to detect outliers 📊  
- Removed outliers using the Interquartile Range (IQR) method 🚫

### 6. Visualizations
- Boxplots illustrating outliers and distributions saved as `boxplots.png` 🖼️

---

## 📁 Deliverables

- **`task1_data_cleaning.ipynb`**: Jupyter notebook containing the full code and analysis workflow  
- **`cleaned_titanic.csv`**: Final cleaned dataset after preprocessing and outlier removal  
- **`boxplots.png`**: Visualization images of `Age` and `Fare` boxplots showing outliers  
- **`README.md`**: This file explaining the project steps and contents

---

## ▶️ How to Use

1. Open and run the `task1_data_cleaning.ipynb` to reproduce the data cleaning steps.  
2. Review the cleaned dataset `cleaned_titanic.csv` for your analysis or modeling.  
3. See the `screenshots/boxplots.png` for visualization insights into data distributions and outliers.  

---

**👤 Submitted by:** Joy Biswas
