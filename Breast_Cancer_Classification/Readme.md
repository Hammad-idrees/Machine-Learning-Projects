# Breast Cancer Prediction using Logistic Regression

## 📌 Overview

This project builds a **Machine Learning model** to predict whether a breast tumor is **Malignant (cancerous)** or **Benign (non-cancerous)** using **Logistic Regression**.

The model is trained using the **Breast Cancer dataset provided by Scikit-learn** and demonstrates how machine learning can assist in medical diagnosis.

---

## 📊 Dataset

The dataset is available in **Scikit-learn's built-in datasets** and contains **30 numerical features** describing characteristics of a tumor such as:

- Radius
- Texture
- Area
- Smoothness
- Concavity
- Perimeter
- Compactness

### Target Classes

The target variable contains two classes:

- **0 → Malignant (Cancerous)**
- **1 → Benign (Non-cancerous)**

---

## 🤖 Model

The project uses **Logistic Regression**, a supervised machine learning algorithm widely used for **binary classification problems**.

The model learns patterns from tumor measurements and predicts whether the tumor is **malignant** or **benign**.

---

## ⚙️ Project Workflow

The main steps involved in this project are:

1. Load the Breast Cancer dataset
2. Convert the dataset into a **Pandas DataFrame**
3. Split the data into **training and testing sets**
4. Apply **feature scaling using StandardScaler**
5. Train the **Logistic Regression model**
6. Evaluate the model using **Accuracy Score**
7. Build a **predictive system for new input data**

---

## 🛠 Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🎯 Objective

The objective of this project is to demonstrate how **Logistic Regression** can be applied to a **medical classification problem** to assist in predicting breast cancer diagnosis based on tumor characteristics.
