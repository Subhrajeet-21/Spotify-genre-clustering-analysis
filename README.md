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

- Data cleaning and preprocessing
- Feature engineering (custom audio metrics)
- Dimensionality reduction using PCA & t-SNE
- K-Means clustering with hyperparameter tuning
- Outlier detection and removal using silhouette scores
- Cluster visualization using Plotly

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

## Results Summary

### Initial Model

* Optimal Clusters (k): **2**
* Silhouette Score: **0.1923**

### After Improvement (t-SNE + Outlier Removal)

* Optimal Clusters (k): **3**
* Final Silhouette Score: **0.3776**
* Improvement: **+0.0026**

---

## 📊 Visualizations  

### 🔹 Elbow Method (Optimal Clusters)
<img width="547" height="393" alt="image" src="https://github.com/user-attachments/assets/f0205ad0-f63a-4e08-8a78-917984914cf5" />


### 🔹 Silhouette Score Analysis
<img width="532" height="398" alt="image" src="https://github.com/user-attachments/assets/72ce0689-c226-4c21-b677-9cde9ea13871" />


### 🔹 Final Clustering (t-SNE Visualization)
<img width="2393" height="634" alt="image" src="https://github.com/user-attachments/assets/6c0a83ae-0d65-48fe-829b-61b85e4fe522" />


---

## 🧪 Model Optimization

* Hyperparameter tuning using Elbow & Silhouette methods
* Removed poorly clustered data points (outliers)
* Improved clustering performance and separation

---
