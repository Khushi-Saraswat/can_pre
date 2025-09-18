

---

# **Cancer Prediction using Machine Learning**

## **Project Overview**

This project is a **Breast Cancer Prediction System** using **Machine Learning in Python**.
The aim is to **predict whether a tumor is malignant or benign** based on input features extracted from breast cancer cell images.

---

## **Dataset**

* **Source:** [Kaggle Breast Cancer Wisconsin Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* **Features:**
  `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`, … (30+ features in total)
* **Target:** `diagnosis` (M = Malignant, B = Benign)

**Preprocessing Steps:**

1. Dropped irrelevant columns: `id` and `Unnamed: 32`
2. Converted `diagnosis` to **categorical type**
3. Checked for missing values using a **heatmap** (`sns.heatmap`)
4. Standardized features using **StandardScaler**

---

## **Algorithms Used**

### **Logistic Regression**

* Used for **binary classification** to predict if a tumor is malignant (M) or benign (B)
* **Why Logistic Regression:**

  * Simple and interpretable model
  * Works well with small to medium-sized datasets

---

## **How to Use**

1. Clone the repository:

```bash
git clone https://github.com/Khushi-Saraswat/Cancer_Pred.git
```

2. Open the notebook in **Google Colab**
3. Run all cells step by step
4. Input new data to predict tumor type

---

## **Libraries Used**

* **pandas** – for data manipulation
* **seaborn** – for data visualization
* **scikit-learn** – for machine learning models and preprocessing

---

## **Conclusion**

* This project demonstrates **binary classification using Logistic Regression**
* Provides a **reliable and interpretable prediction model** for breast cancer detection
* Fully reproducible and can be extended with other algorithms like **Random Forest, SVM, or KNN** for comparison

---


