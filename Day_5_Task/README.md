# 🌳 Task 5: Decision Trees & Random Forests – AI & ML Internship

**Name:** Joy Biswas  

---

## 📋 Overview

This task applies **Decision Tree** and **Random Forest** classifiers to predict heart disease presence using the **Heart Failure Clinical Records Dataset**.  

It demonstrates:
- Training & evaluating decision trees and ensemble models
- Controlling overfitting via limited tree depth
- Feature importance analysis
- Visualizing model decisions & metrics
- Comparing performance with cross-validation

---

## 📂 Dataset

**Source:** [Heart Failure Clinical Records Dataset (GitHub)](https://raw.githubusercontent.com/anik199/Heart-failure-prediction/main/heart.csv)  
**Records:** 918  
**Features:** 12 patient health indicators  
**Target Variable:** `HeartDisease`  
(1 = Disease, 0 = No Disease)

**Preprocessing:**
- Encoded categorical variables (`Sex`, `ExerciseAngina`, `ChestPainType`, `RestingECG`, `ST_Slope`)
- One-hot encoding for multi-category features

---

## ✅ Steps Performed

1. 📥 Load & explore dataset  
2. 🧹 Encode categorical features  
3. 🌳 Train full-depth Decision Tree  
4. ✂️ Limit tree depth (`max_depth=3`) to reduce overfitting  
5. 🌲 Train Random Forest (`n_estimators=100`, `max_depth=5`)  
6. 📊 Evaluate using accuracy & 5‑fold CV  
7. 🔍 Interpret:
   - Tree diagram (`screenshots/decision_tree.png`)
   - Feature importance (`screenshots/feature_importance.png`)
8. 💾 Save cleaned dataset & visualizations

---

## 📈 Results Summary

| Model                             | Test Accuracy | CV Accuracy |
|-----------------------------------|--------------:|------------:|
| Decision Tree (full depth)        | **88.50%**    | **87.30%**  |
| Decision Tree (`max_depth=3`)     | **86.90%**    | **87.30%**  |
| Random Forest (`max_depth=5`)     | **90.20%**    | **89.40%**  |

**Top Features by Random Forest:**  
Shown in `screenshots/feature_importance.png`

---

## 📁 Files in this Folder

- `task5_decision_trees_random_forest.ipynb` / `.py` – Complete code  
- `cleaned_heart_failure.csv` – Final cleaned dataset  
- `screenshots/decision_tree.png` – Visualization of Decision Tree (`max_depth=3`)  
- `screenshots/feature_importance.png` – Feature importance chart  
- `screenshots/confusion_matrix.png` – Confusion Matrix for Random Forest predictions  
- `README.md` – This documentation

---

## ▶️ How to Run

1. Clone this repo or open in Colab/Jupyter.  
2. Install requirements:  
3. Run all cells in the `.ipynb` or `.py` file.  
4. View metrics in console and images in `screenshots/`.  
5. (In Colab) Uncomment `files.download()` lines to save outputs locally.

---

## 📬 Contact

📧 **bjoy1403@gmail.com**  
🐙 Open a GitHub issue in this repo

---

**Author:** Joy Biswas  
**Program:** Elevate AI & ML Internship  

---

⭐ If you find this project useful, please star ⭐ the repo!
