# 🎧 Spotify Genre Clustering & Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📌 Project Overview

This project focuses on grouping Spotify tracks into meaningful **music clusters (genres)** using **unsupervised machine learning techniques**.

Instead of direct classification, the model uses clustering algorithms to discover hidden patterns in audio features such as tempo, energy, and danceability.

---

## 🎯 Key Features

✔️ Data cleaning and preprocessing
✔️ Feature engineering (custom audio metrics)
✔️ Dimensionality reduction using PCA & t-SNE
✔️ K-Means clustering with hyperparameter tuning
✔️ Outlier detection and removal using silhouette scores
✔️ Cluster visualization using Plotly

---

## 📂 Dataset

> ⚠️ Dataset is not included due to GitHub size limitations.

📥 **Download Dataset:**
[(Dataset link)](https://drive.google.com/file/d/1A1OU4azw0C37LYywRQ2cqr6lQ63xr2wz/view?usp=sharing)

After downloading, place it in the directory:

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn

---

## Machine Learning Approach

### 🔹 Algorithms Used

* K-Means Clustering
* PCA (Principal Component Analysis)
* t-SNE (Dimensionality Reduction)

### 🔹 Feature Engineering

Created new features like:

* Rhythmic Complexity
* Vocal Presence
* Acoustic Vibe

---

## 📊 Results Summary

### Initial Model

* Optimal Clusters (k): **2**
* Silhouette Score: **0.1923**

### After Improvement (t-SNE + Outlier Removal)

* Optimal Clusters (k): **3**
* Final Silhouette Score: **0.3776**
* Improvement: **+0.0026**

---

## 📉 Visualizations

* Elbow Method (Optimal k selection)
* Silhouette Score Analysis
* Cluster visualization (PCA & t-SNE)
* Interactive scatter plots using Plotly

---

## 🧪 Model Optimization

* Hyperparameter tuning using Elbow & Silhouette methods
* Removed poorly clustered data points (outliers)
* Improved clustering performance and separation

---
