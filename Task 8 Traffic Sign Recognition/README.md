# 🚦 Traffic Sign Recognition  

## 📌 Project Overview  
This project builds a **Traffic Sign Recognition system** using image classification techniques.  
It leverages **Convolutional Neural Networks (CNNs)** to detect and classify traffic signs from images.  

---

## 🚀 Features  
- **Data Preprocessing**  
  Normalization, resizing, and augmentation of traffic sign images.  
- **Exploratory Data Analysis (EDA)**  
  Visualization of image samples and class distribution.  
- **Deep Learning Model**  
  Implementation of a **CNN** for accurate traffic sign recognition.  
- **Model Evaluation**  
  Uses **accuracy, confusion matrix, and classification report** for performance measurement.  

---

## 📂 Project Structure  
- `Task 8 Traffic Sign Recognition.ipynb` → Main Colab-ready notebook  
- `data/` → Dataset containing traffic sign images (e.g., German Traffic Sign Dataset - GTSRB)  

---

## 🛠️ Installation & Requirements  
Run in **Google Colab** (recommended). If running locally, install dependencies:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras
```

---

## ▶️ How to Use  
1. Download the dataset (e.g., **GTSRB - German Traffic Sign Recognition Benchmark**).  
2. Place the dataset in the working directory.  
3. Open the notebook in **Google Colab** or Jupyter Notebook.  
4. Run the cells step by step:  
   - Load and preprocess dataset  
   - Visualize image samples and class distribution  
   - Train the CNN model  
   - Evaluate performance with accuracy and confusion matrix  
   - Test the model on new traffic sign images  

---

## 📊 Results  
- **CNN Model**: Achieves high accuracy in classifying traffic signs.  
- **Strengths**: Robust to variations in lighting and rotation.  
- **Challenges**: Performance can degrade with low-resolution or noisy images.  

---

## 📌 Author  
Prepared as part of **Task 8: Traffic Sign Recognition** project.  
