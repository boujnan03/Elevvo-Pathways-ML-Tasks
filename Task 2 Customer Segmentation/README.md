# 🛍️ Customer Segmentation — Mall Customers  

---

## 📌 Project Overview  
This project performs **customer segmentation** using the **Mall Customers dataset**.  
The goal is to identify customer groups based on spending habits and income to help businesses improve **marketing strategies** and **targeted promotions**.  

We will:  
- Perform **data cleaning** and **exploratory data analysis (EDA)**  
- Select key features (`Annual Income`, `Spending Score`, `Age`)  
- Apply **feature scaling**  
- Determine the **optimal number of clusters** (Elbow method & Silhouette score)  
- Train a **K-Means clustering model**  
- Visualize clusters in **2D and 3D**  
- Compare with other clustering algorithms (**DBSCAN & Agglomerative**)  

---

## 📂 Dataset Information  
The dataset contains the following attributes:  

- **CustomerID** → Unique identifier  
- **Gender** → Male / Female  
- **Age** → Age of customer  
- **Annual Income (k$)** → Income in thousands  
- **Spending Score (1–100)** → Score assigned by mall based on customer behavior  

---

## ⚙️ Usage (Google Colab Friendly)  
1. Clone this repository or upload the notebook to **Google Colab**.  
2. Obtain the dataset (`Mall_Customers.csv`):  
   - **Option A: Upload CSV** directly into Colab (recommended).  
   - **Option B: Kaggle API** – configure with `kaggle.json`.  
   - **Option C: Google Drive/GitHub** link to dataset.  

---

## 📊 Methods & Models  
- **EDA** → Visualize income, spending, and customer demographics  
- **Clustering**:  
  - **K-Means** (primary method)  
  - **DBSCAN & Agglomerative Clustering** (comparison)  
- **Evaluation**: Elbow Method, Silhouette Score  

---

## 📈 Visualizations  
- **2D scatter plots** of clusters (Income vs Spending Score)  
- **3D visualization** (Age, Income, Spending Score)  
- Cluster heatmaps and distribution plots  

---

## 🛠️ Tech Stack  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (K-Means, DBSCAN, Agglomerative, scaling & metrics)  
- Plotly / Matplotlib 3D visualization  

---

## 🚀 Future Improvements  
- Automate cluster number selection with **Gap Statistics**  
- Apply **Gaussian Mixture Models (GMM)**  
- Test on larger and real-world retail datasets  
- Deploy as a **dashboard** for customer analytics  

---
