<!-- Elegant Header -->
<h1 align="center">🔮 Task 7: Support Vector Machines (SVM) Classification – AI & ML Internship</h1>
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

This task implements **Support Vector Machines (SVM)** for binary classification on the **Breast Cancer Wisconsin dataset**.  
Key steps include:
- Data standardization and dimensionality reduction (PCA for visualization)
- Training SVM with both linear and RBF kernels
- Visualizing decision boundaries (with PCA-reduced features)
- Hyperparameter tuning, accuracy evaluation, and confusion matrix
- Reproducible workflow with code, cleaned data, and all screenshots

The project highlights margin maximization, kernel trick, and practical model evaluation.

</details>

---

## ✅ Task Checklist
| Status | Task |
|--------|------|
| ✔ | 📥 Load and Explore Dataset |
| ✔ | ⚖️ Feature Standardization |
| ✔ | 🔽 Reduce to 2D for Visualization (PCA) |
| ✔ | 🔄 Train SVM with Linear Kernel |
| ✔ | 🌀 Train SVM with RBF Kernel |
| ✔ | 👁️ Visualize Decision Boundaries (PCA space) |
| ✔ | 🛠 Tune Hyperparameters (`C`, `gamma`) |
| ✔ | 📈 Cross-Validation & Accuracy Score |
| ✔ | 📑 Generate Confusion Matrix |
| ✔ | 💾 Save Clean Data and Visualizations |
| ✔ | 📝 Document Workflow in README |

---

## ⚙ Steps

### **1️⃣ Data Loading & Preprocessing**
- Loaded Breast Cancer Wisconsin dataset with scikit-learn
- Standardized features (mean=0, std=1) for SVM compatibility

### **2️⃣ Dimensionality Reduction**
- Applied PCA to reduce features to 2 components for boundary visualization

### **3️⃣ Model Training**
- Trained SVM (linear kernel) and SVM (RBF kernel) classifiers
- Compared their test accuracy

### **4️⃣ Decision Boundary Visualization**
- Plotted decision boundaries for both kernels on the test set (2D PCA space)
- Visualized confusion matrix as heatmap

### **5️⃣ Hyperparameter Tuning**
- Used GridSearchCV for RBF kernel (`C`, `gamma`)
- Reported best CV parameters/scores

### **6️⃣ Output Saving**
- Saved standardized dataset as `cleaned_breast_cancer_svm.csv`
- Saved decision boundary and confusion matrix plots to `screenshots/`

---

## 📊 Results Summary

| Model               | Test Accuracy |
|---------------------|-------------:|
| SVM (Linear Kernel) | **0.973**    |
| SVM (RBF Kernel)    | **0.982**    |

- **Best RBF Params (GridSearch):** Output shown in notebook/run (e.g., `C=1`, `gamma='scale'`)
- Decision boundaries for both kernels, and confusion matrix for RBF, included in screenshots

---

## 📂 Code Structure

Task7/
│── task7_svm_classification.ipynb # Full notebook/script
│── cleaned_breast_cancer_svm.csv # Standardized input features
│── screenshots/
│ ├── svm_linear_decision_boundary.png
│ ├── svm_rbf_decision_boundary.png
│ └── svm_rbf_confusion_matrix.png
│── README.md # Documentation
---

## 📁 Deliverables
- The complete Task 7 notebook/script with all code
- Cleaned and standardized CSV dataset
- Visualizations for decision boundaries (linear & RBF), confusion matrix
- This README.md file for reviewers

---

## ▶ How to Use
1. Run `task7_svm_classification.ipynb`/`.py` in Jupyter or Colab
2. Install requirements if needed:
3. Execute all cells for data preprocessing, model training, tuning, and visualization
4. Check results in the `screenshots/` folder
5. (Colab) Uncomment `files.download()` lines to download outputs locally

---

## 👤 Author
**Joy Biswas**  
Elevate AI & ML Internship participant

---

## 🏆 GitHub Achievements
*Add your badges, GitHub trophies, or highlight your profile here if desired.*

---

⭐ *Thank you for visiting and reviewing! If you found this work helpful, please star the repository!* ⭐
