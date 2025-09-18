Cancer Prediction using Machine Learning
Project Overview

This project is a Breast Cancer Prediction System using Machine Learning in Python.
The aim is to predict whether a tumor is malignant or benign based on input features extracted from breast cancer cell images.

Dataset

Source: Kaggle Breast Cancer Wisconsin Dataset

Features:

radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, ... (30+ features in total)

Target: diagnosis (M = Malignant, B = Benign)

Preprocessing done:

Dropped irrelevant columns like id and Unnamed: 32

Converted diagnosis to categorical type

Checked for missing values using heatmap (sns.heatmap)

Standardized features using StandardScaler


Algorithms Used
1️⃣ Logistic Regression

Logistic Regression is used for binary classification.

It predicts the probability of a tumor being malignant (M) or benign (B).

Why Logistic Regression:

Simple, interpretable model

Works well with small to medium-sized datasets

How to Use

Clone the repository:

git clone https://github.com/Khushi-Saraswat/Cancer_Pred.git


Open the notebook in Google Colab.

Run all cells step by step.

Input new data to predict tumor type.


Libraries Used

pandas – for data manipulation

seaborn – data visualization

scikit-learn – machine learning models and preprocessing

Conclusion

This project demonstrates binary classification using Logistic Regression.
It provides a reliable, interpretable prediction model for breast cancer detection.

✅ The notebook is fully reproducible and can be extended with other algorithms like Random Forest, SVM, or KNN for comparison.
