# 🫀 Heart Disease Prediction using Machine Learning (SVM & Logistic Regression)

This repository contains a machine learning project focused on predicting the presence of heart disease using two classification algorithms: **Support Vector Machine (SVM)** and **Logistic Regression**.

---

## 📌 Project Overview

Heart disease is a leading cause of mortality worldwide. Early prediction can help in timely treatment and potentially save lives. This project uses clinical data to classify whether a patient has heart disease or not (`1 = Defective`, `0 = Non-Defective`).

---

## 💡 Objectives

- Load and explore the dataset
- Preprocess the data (scaling, stratified split)
- Train models using SVM and Logistic Regression
- Evaluate model performance with:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Visualize results and make comparisons

---

## 📊 Dataset
The dataset contains the following **features**:

1. **age** – Age of the patient
2. **sex** – Sex (1 = male; 0 = female)
3. **cp** – Chest pain type (0–3, indicating severity/type)
4. **trestbps** – Resting blood pressure (in mm Hg)
5. **chol** – Serum cholesterol (in mg/dl)
6. **fbs** – Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. **restecg** – Resting electrocardiographic results (values 0, 1, 2)
8. **thalach** – Maximum heart rate achieved
9. **exang** – Exercise induced angina (1 = yes; 0 = no)
10. **oldpeak** – ST depression induced by exercise relative to rest
11. **slope** – Slope of the peak exercise ST segment
12. **ca** – Number of major vessels (0–3) colored by fluoroscopy
13. **thal** – Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect)
14. **target** – Target variable (1 = heart disease, 0 = no heart disease)

Dataset source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease) / [Kaggle](https://www.kaggle.com/datasets)

---

## 🛠️ Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - `Pandas`, `NumPy` – Data manipulation
  - `Matplotlib`, `Seaborn` – Visualization
  - `Scikit-learn` – ML models and evaluation

---

## 📈 Results

| Model               | Accuracy (Test) | Accuracy (Train) |
|--------------------|------------------|------------------|
| Logistic Regression| 81.96%           | 85.12%           |
| SVM (Linear Kernel)| 81.96%           | —                |

> Both models achieved similar test accuracy. Logistic Regression showed slightly better performance on training data. Future improvements can include hyperparameter tuning or using ensemble methods.


