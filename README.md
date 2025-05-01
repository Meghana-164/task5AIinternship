# Task 5: Decision Trees and Random Forests - Heart Disease Prediction

##  Project Overview
This project focuses on building classification models using **Decision Trees** and **Random Forests** to predict the presence of heart disease based on patient health data. The dataset used includes 1025 entries and 14 medical attributes.

---

##  Objectives
- Implement a **Decision Tree classifier** to understand model interpretability.
- Train a **Random Forest classifier** to enhance prediction accuracy.
- Visualize the decision-making process and feature importance.
- Evaluate models using metrics such as accuracy and cross-validation.

---

## 📁Dataset
- **Name:** Heart Disease Dataset
- **Entries:** 1025
- **Features:** 14 (e.g., age, sex, cp, trestbps, chol, thalach, etc.)
- **Target:** Presence of heart disease (0 = No Disease, 1 = Disease)

---

## ⚙Models and Results

###  Decision Tree
- **Training Accuracy:** `85.12%`
- **Testing Accuracy:** `78.05%`
- A fully grown tree was visualized to understand decision paths and splits.

###  Random Forest
- **Cross-Validation Accuracy Scores:** `[1.0, 1.0, 1.0, 1.0, 0.985]`
- **Mean CV Accuracy:** `99.7%`
- More stable and accurate due to ensemble learning.

---

## 📈 Visualizations

###  Decision Tree Plot
- Shows how the tree splits based on different features.
- Reveals overfitting due to deep structure.

###  Feature Importances (from Random Forest)
Top contributing features:
- `cp` (chest pain type)
- `thalach` (maximum heart rate)
- `oldpeak` (ST depression)
- `ca` (number of major vessels)
- `thal` (thalassemia)

Least contributing:
- `fbs`, `sex`, `restecg`

---

## 🧠Interpretation
- The Decision Tree overfits the training data.
- The Random Forest generalizes better and delivers high performance.
- Feature importance visualization aids in understanding which variables are most influential in prediction.

---

## Conclusion
- **Random Forests** outperformed individual Decision Trees.
- The project highlights the trade-off between interpretability and performance.
- Ensemble models offer robustness and better generalization.

---

## 🛠Tools and Libraries
- Python
- Scikit-learn
- Matplotlib
- Seaborn
- Graphviz (for tree visualization)

---



