# Breast Cancer Wisconsin ML Project

## 🧪 Project Overview
This project uses the **Breast Cancer Wisconsin dataset** to predict whether a tumor is **malignant or benign** using Machine Learning algorithms. It compares three ensemble models:

- Random Forest Classifier  
- Gradient Boosting Classifier  
- AdaBoost Classifier  

The models are evaluated based on **Precision, Recall, and F1-Score**, and the best-performing model is identified.



## 📂 Dataset
- Source: [scikit-learn `load_breast_cancer`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)  
- Features: 30 numeric features (mean, standard error, and worst of various cell characteristics)  
- Target: Binary (0 = malignant, 1 = benign)  
- Samples: 569



## ⚙️ Requirements
Python 3.x and the following packages:

```text
pandas
numpy
scikit-learn
