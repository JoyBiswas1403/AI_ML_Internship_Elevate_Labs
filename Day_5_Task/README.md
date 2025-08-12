<!-- Elegant Header -->
<h1 align="center">🌳 Task 5: Decision Trees & Random Forests – AI & ML Internship</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Status-✅%20Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/badge/Dataset-Heart%20Failure-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## 📜 Table of Contents
- [📖 About](#-about)
- [✅ Task Checklist](#-task-checklist)
- [⚙ Steps](#-steps)
- [📊 Results Summary](#-results-summary)
- [📂 Code Structure](#-code-structure)
- [📁 Deliverables](#-deliverables)
- [▶ How to Use](#-how-to-use)
- [👤 Author](#-author)
- [🏆 GitHub Achievements](#-github-achievements)  <!-- Optional, keep if relevant -->

---

## 📖 About
<details>
<summary><b>🔍 Click to expand</b></summary>

This task implements **Decision Tree** and **Random Forest** classifiers to predict heart disease presence using the **Heart Failure Clinical Records Dataset**.

Key objectives include:
- Training and evaluating tree-based models  
- Controlling overfitting by limiting tree depth  
- Interpreting model outputs via feature importance  
- Visualizing decision trees, feature importances, and confusion matrices  
- Comparing models using accuracy and cross-validation  

The project demonstrates effective classification model building with clear insights and reproducible results.

</details>

---

## ✅ Task Checklist
| Status | Task |
|--------|------|
| ✔ | 📥 Load & Explore Dataset |
| ✔ | 🧹 Encode Categorical Features |
| ✔ | 🌳 Train Decision Tree (full depth + limited depth) |
| ✔ | 🌲 Train Random Forest Classifier |
| ✔ | 📊 Evaluate Models with Accuracy and Cross-Validation |
| ✔ | 🔍 Visualize Tree, Feature Importance, Confusion Matrix |
| ✔ | 💾 Save Processed Data and Visualizations |
| ✔ | 📝 Document Process and Results in README |

---

## ⚙ Steps

### **1️⃣ Load & Explore**
- Loaded dataset from [Heart Failure Clinical Records GitHub](https://raw.githubusercontent.com/anik199/Heart-failure-prediction/main/heart.csv)  
- Examined datatypes, missing values, and feature distributions  

### **2️⃣ Data Preprocessing**
- Encoded `Sex`, `ExerciseAngina` as binary  
- One-hot encoded `ChestPainType`, `RestingECG`, `ST_Slope`

### **3️⃣ Train Models**
- Decision Tree (full depth)  
- Decision Tree (`max_depth=3`) to reduce overfitting  
- Random Forest (`n_estimators=100`, `max_depth=5`)

### **4️⃣ Evaluate**
- Calculated accuracy on test data  
- Performed 5-fold cross-validation  
- Generated confusion matrix

### **5️⃣ Visualize**
- Plotted Decision Tree diagram (`decision_tree.png`)  
- Visualized Random Forest feature importance (`feature_importance.png`)  
- Displayed confusion matrix heatmap (`confusion_matrix.png`)

### **6️⃣ Save Outputs**
- Cleaned and encoded dataset saved as `cleaned_heart_failure.csv`  
- All visualizations saved in `screenshots/` folder

---

## 📊 Results Summary

| Model                             | Test Accuracy | CV Accuracy |
|-----------------------------------|--------------:|------------:|
| Decision Tree (full depth)        | **88.50%**    | **87.30%**  |
| Decision Tree (`max_depth=3`)     | **86.90%**    | **87.30%**  |
| Random Forest (`max_depth=5`)     | **90.20%**    | **89.40%**  |

---

## 📂 Code Structure

---

## 📁 Deliverables

- Complete Task 5 notebook/script implementing Decision Trees and Random Forests  
- Cleaned and preprocessed dataset ready for modeling  
- Visualizations for model interpretability and evaluation  
- This detailed README file documenting process, results, and usage  

---

## ▶ How to Use

1. Open the notebook/script `task5_decision_trees_random_forest.ipynb` in Jupyter or Google Colab  
2. Install requirements if needed:
3. Run all cells to reproduce:
- Data loading and preprocessing  
- Model training and evaluation  
- Visualization generation  
4. Check the `screenshots/` folder for saved images  
5. (In Colab) Uncomment download lines to save files locally

---

## 👤 Author

**Joy Biswas**  
Elevate AI & ML Internship participant  

---

## 🏆 GitHub Achievements

*You can optionally include badges or highlight your GitHub profile here.*

---

⭐ _Thank you for reviewing this work! If it helped you, please star the repository!_ ⭐

