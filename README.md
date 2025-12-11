# Telco-Customer-Churn-Prediction-using-Decision-Tree

📌 Overview

This project predicts telecom customer churn using a Decision Tree Classifier.
The dataset contains customer details, services used, charges, and whether the customer left the service.

📁 Dataset

File used:
WA_Fn-UseC_-Telco-Customer-Churn (1).csv

Target column: Churn (Yes → 1, No → 0)

🔧 Technologies

Python

Pandas, NumPy

Scikit-Learn

Matplotlib, Seaborn

🚀 Steps Performed

Load and clean data

Convert categorical data using one-hot encoding

Train/Test split (80/20)

Train a Decision Tree model

Evaluate using:

Accuracy

Classification report

Confusion matrix + heatmap

Extract top 5 important features

📊 Output

Model accuracy

Precision, Recall, F1-score

Confusion matrix visualization

Top features that influence churn

▶ How to Run in Google Colab

Upload the CSV:

from google.colab import files
files.upload()


Run the full code.
