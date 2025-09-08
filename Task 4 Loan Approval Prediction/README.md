# Loan Approval Prediction

## 📌 Project Overview
This project aims to **predict whether a loan application will be approved** using applicant and loan features.  
It follows a complete machine learning workflow: data cleaning, exploratory analysis, model training, evaluation, and handling class imbalance.  

The final deliverable is a **Google Colab-ready notebook** with a clean and reproducible pipeline.

---

## 🚀 Features
- Load and preprocess the Kaggle **Loan Approval Prediction Dataset**.
- Handle **missing values**, **categorical encoding**, and **feature scaling**.
- Perform **Exploratory Data Analysis (EDA)** with class distribution and feature relationships.
- Train baseline classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
- Evaluate models with:
  - Precision, Recall, F1-score, Accuracy
  - ROC-AUC
  - Confusion Matrices
- Address **class imbalance** using **SMOTE**.
- Hyperparameter tuning with **GridSearchCV**.

---

## 📂 Project Structure
- `Task 4 Loan Approval Prediction.ipynb` → Main notebook with full workflow
- `loan.csv` (or dataset from Kaggle) → Input dataset

---

## 🛠️ Installation & Requirements
Run in **Google Colab** (recommended). If running locally, install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost
```

---

## ▶️ How to Use
1. Open the notebook in **Google Colab**.
2. Upload the Kaggle dataset (`loan.csv`).
3. Run all cells sequentially.
4. Review model performance and comparisons at the end.

---

## 📊 Results
- Baseline models trained and compared.
- Improved performance after **SMOTE oversampling**.
- Precision emphasized as the key metric due to imbalanced dataset.

---

## 📌 Author
Prepared as part of **Task 4: Loan Approval Prediction** project.

---
