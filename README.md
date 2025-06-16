# email-spam-classifier

# 📨 Email Spam Classifier - Logistic Regression (from Scratch)

This project implements a spam email classifier using **Logistic Regression from scratch (no sklearn models)**, trained on a real-world high-dimensional dataset with over **3000 word features** per email.

---

## 📌 Problem Statement

Build a machine learning model that can classify emails as **spam (1)** or **not spam (0)** using logistic regression without using high-level ML libraries.

---

## 🧠 What I Learned

- Implemented the **sigmoid function**, **cost function**, **gradient calculation**, and **gradient descent algorithm** using only **NumPy**
- Worked with **high-dimensional** data (3000 features)
- Applied **feature scaling** for better convergence
- Used **L2 Regularization** to prevent overfitting
- Evaluated the model with **accuracy, precision, recall, F1-score**, and **confusion matrix**

---

## 📊 Dataset

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)
- 5172 emails, each represented by:
  - 1 identifier column
  - 3000 columns representing frequency of the most common words
  - 1 label column (1 = spam, 0 = not spam)

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Google Colab

---

## 🚀 Model Overview

Train Accuracy	99.98%
Test Accuracy 	96.91%
Precision     	91%
Recall	        99%
F1-score      	95%

---

## 📈 Training Visualization

- 📉 Cost function decreasing over iterations
- ✅ Confusion matrix showing correct vs incorrect predictions

---
