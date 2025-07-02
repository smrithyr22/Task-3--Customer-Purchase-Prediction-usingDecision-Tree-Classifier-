# 📌Task-3-Customer Purchase Prediction usingDecision Tree Classifier

This repository contains the implementation of a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral features. The project uses the Bank Marketing Dataset from the UCI Machine Learning Repository.

## 🧠 Objective

To build and evaluate a decision tree classification model that predicts a customer's likelihood of purchasing a product or service, assisting in targeted marketing strategies.

## 🗂️ Dataset

Source: UCI Machine Learning Repository

Name: Bank Marketing Dataset

Target Variable: y (subscription to term deposit - yes/no)

## 📊 Steps Followed

1. Data Loading and Exploration
2. Data Preprocessing and Encoding
3. Feature Selection
4. Model Building using Decision Tree Classifier
5. Model Evaluation using accuracy, confusion matrix, precision, recall, and F1-score
6. Visualization of the Decision Tree

## 🧪 Notebook Highlights

- **Library Import**: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`
- **Preprocessing**:
  - Encoding categorical features using `LabelEncoder`
  - Splitting data into training and testing sets (70/30)
- **Modeling**:
  - Fitting `DecisionTreeClassifier`
  - Model accuracy: **~87.29%**
  - Confusion Matrix and Classification Report
- **Visualization**:
  - Heatmap of Confusion Matrix
  - Visual representation of the Decision Tree

---

## 📊 Model Evaluation Metrics

Accuracy Score: 87.29%

Confusion Matrix: [[11105   861]                         [  863   735]]


## 🔧 Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib & Seaborn (for data visualization)

Jupyter Notebook


## 📁 Status
✅ Task 03 completed as part of the SkillCraft Technology Data Science Internship
