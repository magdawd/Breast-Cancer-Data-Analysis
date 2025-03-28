# Breast Cancer Data Analysis Project

## Overview
This project analyzes the **Breast Cancer Wisconsin (Original) Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/15/breast+cancer+wisconsin+original). The goal is to classify tumors as **benign** or **malignant** using different machine learning models.

## Steps in the Project

### **1. Data Preprocessing**
- Load the dataset and create a DataFrame.
- Handle missing values.
- Drop redundant columns.
- Convert target values to binary format.

### **2. Exploratory Data Analysis (EDA)**
- Plot the count of benign and malignant cases.
- Generate a correlation heatmap.

### **3. Data Splitting & Standardization**
- Split the dataset into **80% training** and **20% testing**.
- Standardize the features for better model performance.

### **4. Model Training & Evaluation**
- Selected models based on [Scikit-learn’s cheat sheet](https://scikit-learn.org/stable/machine_learning_map.html).
- Trained multiple classifiers:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)

### **5. Performance Evaluation**
- Calculated accuracy for each model.
- Plotted:
  - Accuracy comparisons.
  - Confusion matrices.
  - ROC curves and AUC scores.
  - Feature importance (for Random Forest).
