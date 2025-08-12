<!-- Elegant Header -->
<h1 align="center">🤖 Task 6: K-Nearest Neighbors (KNN) Classification – AI & ML Internship</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Status-✅%20Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" />
  <img src="https://img.shields.io/badge/Dataset-Iris-lightgrey?style=for-the-badge" />
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
- [🏆 GitHub Achievements](#-github-achievements)

---

## 📖 About
<details>
<summary><b>🔍 Click to expand</b></summary>

This task implements the **K-Nearest Neighbors (KNN)** algorithm for multi-class classification using the classic **Iris dataset**.  
Main goals:
- Normalize features for fair distance measurement
- Train and evaluate KNN models for multiple K values
- Visualize accuracy trends and model performance
- Outputs include code, a cleaned dataset, plots, and confusion matrix for reproducibility

The project demonstrates instance-based learning and helps select optimal hyperparameters for practical classification tasks.

</details>

---

## ✅ Task Checklist
| Status | Task |
|--------|------|
| ✔ | 📥 Load and Explore Dataset |
| ✔ | ⚖️ Normalize Features |
| ✔ | 🧑‍🤝‍🧑 Train KNN Classifiers for Various K |
| ✔ | 📊 Plot Accuracy for K Selection |
| ✔ | 📈 Evaluate Best KNN Model on Test Data |
| ✔ | 📑 Generate and Plot Confusion Matrix |
| ✔ | 💾 Save Scaled Dataset and Visualizations |
| ✔ | 📝 Document Process and Results in README |

---

## ⚙ Steps

### **1️⃣ Load & Explore**
- Loaded dataset using scikit-learn's Iris loader  
- Explored features, target variables, and checked for missing data

### **2️⃣ Normalize Features**
- Used StandardScaler to make all features mean=0, std=1 for better KNN performance

### **3️⃣ Train KNN Classifiers**
- Trained KNN models for K from 1 to 20
- Recorded train/test accuracy for each K

### **4️⃣ Evaluate & Select Best K**
- Selected K value giving highest test accuracy
- Predicted on test set with best K

### **5️⃣ Visualizations**
- Plotted accuracy vs. K graph (`knn_accuracy.png`)
- Created annotated confusion matrix for best K (`knn_confusion_matrix.png`)

### **6️⃣ Save Outputs**
- Merged and saved scaled training/testing features as `cleaned_iris_scaled.csv`
- Plots saved in `screenshots/`

---

## 📊 Results Summary

| Metric                   | Value      |
|--------------------------|-----------:|
| Best K                   | **6**      |
| Test Accuracy (Best K)   | **1.00**   |
| Train Acc Range          | 0.96 – 1.00|
| Test Acc Range           | 0.93 – 1.00|

- Detailed confusion matrix and accuracy curves are included in the screenshots.

---

## 📂 Code Structure

Task6/
│── task6_knn_classification.ipynb
│── cleaned_iris_scaled.csv
│── README.md
│── screenshots/
│     ├── knn_accuracy.png
│     └── knn_confusion_matrix.png


---

## 📁 Deliverables

- Complete Task 6 KNN classification notebook or script
- Scaled and cleaned CSV of features + labels
- Two critical visualizations for evaluation and explainability
- Full documentation with explanation and instructions

---

## ▶ How to Use

1. Open and run `task6_knn_classification.ipynb` (or `.py`) in Jupyter or Colab  
2. Install requirements if needed:
3. Run all cells to reproduce preprocessing, model building, and analysis  
4. View results in the `screenshots/` folder  
5. (Colab) Uncomment download lines to fetch outputs locally

---

## 👤 Author

**Joy Biswas**  
Elevate AI & ML Internship participant  

---

## 🏆 GitHub Achievements

*Optionally add badges, GitHub trophies, or highlight your public profile here.*

---

⭐ _Thank you for reviewing this work! If it helped you, please star the repository!_ ⭐

