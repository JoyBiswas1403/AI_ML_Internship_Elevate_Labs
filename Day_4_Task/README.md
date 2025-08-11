<!-- Elegant Header -->
<h1 align="center">🧬 Task 4: Classification with Logistic Regression – AI & ML Internship</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Status-✅%20Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/badge/Dataset-Breast%20Cancer-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## 📜 Table of Contents
- [📖 About](#-about)
- [✅ Task Checklist](#-task-checklist)
- [⚙ Steps](#-steps)
- [📝 Key Evaluation Metrics](#-key-evaluation-metrics)
- [📂 Code Structure](#-code-structure)
- [📁 Deliverables](#-deliverables)
- [▶ How to Use](#-how-to-use)
- [👤 Author](#-author)

---

## 📖 About
<details>
<summary><b>🔍 Click to expand</b></summary>

This task involves building a **binary classifier** using **Logistic Regression** to predict whether a tumor is malignant or benign based on features from the **Breast Cancer Wisconsin dataset**.

Main objectives include:
- Loading and preparing the dataset  
- Splitting data into stratified training and testing sets  
- Standardizing features for improved model performance  
- Training a logistic regression classifier  
- Evaluating using confusion matrix, precision, recall, ROC curve, and ROC-AUC  
- Visualizing the sigmoid function and important model metrics  
- Saving the cleaned data and outputs for documentation and presentation  

This provides a clear and practical example of logistic regression for medical diagnosis applications.

</details>

---

## ✅ Task Checklist
| Status | Task |
|--------|------|
| ✔ | 📥 Load Breast Cancer Wisconsin dataset |
| ✔ | ➗ Stratified train-test split (80-20) |
| ✔ | ⚖️ Standardize features (mean=0, variance=1) |
| ✔ | 🤖 Train Logistic Regression classifier |
| ✔ | 📊 Evaluate with confusion matrix, precision, recall |
| ✔ | 📈 Plot ROC Curve & calculate ROC-AUC |
| ✔ | 🎚 Visualize sigmoid function |
| ✔ | 💾 Save cleaned dataset and generated visualizations |

---

## ⚙ Steps

### **1️⃣ Load Dataset**
- Loaded the Breast Cancer Wisconsin dataset using scikit-learn's `load_breast_cancer()` function.

### **2️⃣ Data Preparation**
- Created feature matrix and target vector.  
- Split data into training and test sets with 80-20 stratified sampling to maintain class balance.  

### **3️⃣ Feature Scaling**
- Standardized all features to zero mean and unit variance using `StandardScaler`.

### **4️⃣ Model Training**
- Trained a logistic regression model on the standardized training data.

### **5️⃣ Prediction & Evaluation**
- Predicted labels and probabilities on the test set.  
- Computed confusion matrix, precision, recall, and ROC-AUC score.

### **6️⃣ Visualization**
- Plotted confusion matrix heatmap.  
- Generated ROC Curve with AUC annotation.  
- Visualized the sigmoid function to illustrate probability mapping.

### **7️⃣ Saving Outputs**
- Saved the cleaned dataset to CSV.  
- Saved all plots (confusion matrix, ROC curve, sigmoid curve) in the `screenshots/` folder.

---

## 📝 Key Evaluation Metrics

- **Precision:** Ratio of correctly predicted positive observations to total predicted positives.  
- **Recall:** Ratio of correctly predicted positive observations to all actual positives.  
- **ROC-AUC:** Measures overall ability of model to distinguish between classes as threshold varies.  
- **Confusion Matrix:** Provides counts of true positives, true negatives, false positives, and false negatives.

---

## 📂 Code Structure
Task4/
│── task4_logistic_regression.ipynb # Full workflow notebook or script
│── cleaned_breast_cancer.csv # Standardized, cleaned dataset
│── screenshots/
│ ├── confusion_matrix.png # Confusion matrix visualization
│ ├── roc_curve.png # ROC curve and AUC plot
│ └── sigmoid_curve.png # Sigmoid function plot
│── README.md # Documentation for Task 4
---

## 📁 Deliverables

- Complete logistic regression notebook or script for classification task  
- Cleaned and standardized breast cancer dataset CSV  
- Visualization images: confusion matrix, ROC curve, sigmoid function  
- This README file documenting the project details and results  

---

## ▶ How to Use

1. Open and run `task4_logistic_regression.ipynb` (or `.py`) in Jupyter Notebook or Google Colab.  
2. Ensure dependencies are installed:
3. Run all cells to reproduce dataset preparation, model training, evaluation, and visualizations.  
4. Check the `screenshots/` folder for saved images of plots.  
5. (In Colab) Uncomment download commands if you wish to download outputs locally.

---

## 👤 Author

**Joy Biswas**  

---

⭐ _Thank you for visiting! If this project helped you, please consider giving it a star!_ ⭐
