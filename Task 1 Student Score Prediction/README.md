# 🎓 Student Score Prediction — Linear & Polynomial Regression  

*Dataset: Student Performance Factors (Kaggle)*  

---

## 📌 Project Overview  
This project develops a **machine learning regression pipeline** to predict students’ **exam scores** using the **Student Performance Factors** dataset.  

We will:  
- Perform **data cleaning** and **exploratory data analysis (EDA)**  
- Split the dataset into **training & testing sets**  
- Train a **Linear Regression** model to estimate final scores  
- Evaluate the model using **MAE, MSE, RMSE, and R²**  
- Visualize **Actual vs. Predicted** results  
- *Bonus:* Experiment with **Polynomial Regression** and feature engineering (e.g., adding/removing features like `Sleep`, `Participation`, etc.)  

---

## ⚙️ Usage (Google Colab Friendly)  
1. Clone this repository or upload the notebook to **Google Colab**.  
2. Obtain the dataset from **Kaggle** (Student Performance Factors).  
   - **Option A: Kaggle API** (recommended) – place your `kaggle.json` API token and download automatically.  
   - **Option B: Manual Upload** – upload the CSV file (e.g., `Student Performance Factors.csv`) when prompted.  

---

## 📂 Dataset Information  
Expected columns in the dataset:  

```
Hours_Studied, Attendance, Parental_Involvement, Access_to_Resources, 
Extracurricular_Activities, Sleep_Hours, Previous_Scores, Motivation_Level, 
Internet_Access, Tutoring_Sessions, Family_Income, Teacher_Quality, School_Type, 
Peer_Influence, Physical_Activity, Learning_Disabilities, 
Parental_Education_Level, Distance_from_Home, Gender, Exam_Score
```

- **Target variable:** `Exam_Score`  
- **Features:** All other columns  

---

## 📊 Evaluation Metrics  
The models are evaluated using:  
- **MAE (Mean Absolute Error)**  
- **MSE (Mean Squared Error)**  
- **RMSE (Root Mean Squared Error)**  
- **R² Score (Coefficient of Determination)**  

---

## 🛠️ Tech Stack  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (Linear & Polynomial Regression, train/test split, evaluation metrics)  

---

## 🚀 Future Improvements  
- Add **regularization techniques** (Ridge, Lasso)  
- Explore **tree-based models** (Random Forest, XGBoost)  
- Perform **hyperparameter tuning**  
- Deploy as a simple **web app** for score prediction  

---
