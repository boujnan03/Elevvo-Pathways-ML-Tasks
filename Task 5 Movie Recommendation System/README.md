# 🎬 Movie Recommendation System 

## 📌 Project Overview
This project builds a **Movie Recommendation System** using the **MovieLens 100K dataset**.  
It explores three approaches to collaborative filtering and evaluates their performance.

---

## 🚀 Features
- **User-Based Collaborative Filtering**  
  Recommendations based on similarity between users.
- **Item-Based Collaborative Filtering**  
  Recommendations based on similarity between items (movies).
- **Matrix Factorization with Truncated SVD**  
  Dimensionality reduction approach for latent factors.
- **Evaluation with Precision@K**  
  Measures how relevant the recommendations are.

---

## 📂 Project Structure
- `Task 5 Movie Recommendation System.ipynb` → Main Colab-ready notebook  
- `u.data` / `u.item` (from MovieLens 100K dataset) → Input files  

---

## 🛠️ Installation & Requirements
Run in **Google Colab** (recommended). If running locally, install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ How to Use
- Download the **MovieLens 100K dataset** from [GroupLens](https://grouplens.org/datasets/movielens/100k/).  
- Place the data files (`u.data`, `u.item`) in the working directory.  
- Open the notebook in **Google Colab** or Jupyter Notebook.  
- Run the cells step by step:
  - Load and preprocess dataset  
  - Apply collaborative filtering techniques  
  - Generate recommendations  
  - Evaluate with Precision@K  

---

## 📊 Results
- **User-Based CF**: Works well for dense datasets but struggles with sparse users.  
- **Item-Based CF**: More stable, better at capturing similarities across movies.  
- **SVD (Matrix Factorization)**: Produces the best balance of accuracy and generalization.  

---

## 📌 Author
Prepared as part of **Task 5: Movie Recommendation System** project.  
