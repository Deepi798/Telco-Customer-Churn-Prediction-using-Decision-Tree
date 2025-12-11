# Telco-Customer-Churn-Prediction-using-Decision-Tree



# 📄 **README — Telco Customer Churn Prediction**

## 📌 Overview

This project predicts telecom customer churn using a **Decision Tree Classifier**.
The dataset contains customer details, services used, charges, and whether the customer left the service.

---

## 📁 Dataset

File used:
`WA_Fn-UseC_-Telco-Customer-Churn (1).csv`

Target column: **Churn** (Yes → 1, No → 0)

---

## 🔧 Technologies

* Python
* Pandas, NumPy
* Scikit-Learn
* Matplotlib, Seaborn

---

## 🚀 Steps Performed

1. Load and clean data
2. Convert categorical data using one-hot encoding
3. Train/Test split (80/20)
4. Train a **Decision Tree model**
5. Evaluate using:

   * Accuracy
   * Classification report
   * Confusion matrix + heatmap
6. Extract top 5 important features

---

## 📊 Output

* Model accuracy
* Precision, Recall, F1-score
* Confusion matrix visualization
* Top features that influence churn

---

## ▶ How to Run in Google Colab

1. Upload the CSV:

```python
from google.colab import files
files.upload()
```

2. Run the full code.


