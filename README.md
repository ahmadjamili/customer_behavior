# 🧠 Customer Behaviour Clustering

This project focuses on segmenting customers based on their purchase history using unsupervised machine learning. It uses K-Means clustering to uncover meaningful patterns in customer behavior, such as purchasing frequency and monetary value.

## 📌 Challenge

This project was developed in response to a problem posted on Quera:
👉 [Quera Problem Link](https://quera.org/problemset/287262)

Achieved **92% accuracy** on Quera — models with above 90% accuracy were considered correct.

---

## 🚀 Overview

The pipeline performs the following tasks:

1. **Data Cleaning**: Handles missing values and duplicates.
2. **Feature Engineering**:
   - Recency, Frequency, and Monetary value (RFM features)
   - City name encoding with rare label handling
3. **Scaling**: Normalizes selected features using `StandardScaler`.
4. **Clustering**: Applies K-Means clustering to group similar customers.
5. **Evaluation**: Uses **Silhouette Score** to evaluate clustering performance.

---

## 🧰 Tech Stack

- Python 🐍
- Pandas
- scikit-learn
- NumPy
- Jupyter Notebook
- Joblib
- KMeans Clustering

---

## 📁 Project Structure

