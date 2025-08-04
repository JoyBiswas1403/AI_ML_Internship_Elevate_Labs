# Task 1: Data Cleaning & Preprocessing 

This project covers full data cleaning and preprocessing on the Titanic dataset.

---

## Task Checklist

1. **Import and Explore Data**
2. **Handle Missing Values**
3. **Encode Categorical Features**
4. **Normalize/Standardize Numerical Data**
5. **Detect and Remove Outliers**

---

## Steps

### 1. Import and Explore
- Loaded Titanic dataset ([link](https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv))
- Checked data types, shape, and null values (`.info()` and `.isnull().sum()`)

### 2. Handle Missing Values
- Filled missing `Age` values with median.

### 3. Encoding Categorical Variables
- Converted `Sex` to numeric (0 for male, 1 for female).

### 4. Normalization/Standardization
- Standardized `Age` and `Fare` using `(x - mean) / std`.

### 5. Outlier Detection & Removal
- Used boxplots and the IQR rule to remove outlier rows for `Age` and `Fare`.

### 6. Visualizations
- Boxplots saved as `boxplots.png`.

---

## Instructions

1. Open `task1_data_cleaning.ipynb` to view and run the workflow.
2. `cleaned_titanic.csv` is the final cleaned dataset.
3. `boxplots.png` is a visualization of outliers (add as needed).

---

**Submitted by:** Joy Biswas
