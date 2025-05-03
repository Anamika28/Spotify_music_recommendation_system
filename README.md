# Music Recommendation System 🎵

This project implements a personalized music recommendation engine using collaborative filtering and hybrid techniques. It predicts user preferences based on historical interactions and suggests songs accordingly.

## 🔍 Overview

The system explores three major approaches to recommendation:

- **User-User Collaborative Filtering** using KNN
- **Item-Item Collaborative Filtering** using KNN
- **Matrix Factorization** using Singular Value Decomposition (SVD)
- **Hybrid Model**: Weighted combination of SVD and Content-Based Filtering

## 📊 Features

- Preprocessing of user-song rating data
- Evaluation using RMSE, precision, and recall
- Cold-start handling using content-based fallback
- Visualization of model performance and predictions

## 🛠️ Tech Stack

- **Python**: Core logic
- **Surprise Library**: Collaborative filtering algorithms
- **Pandas & NumPy**: Data manipulation
- **Matplotlib & Seaborn**: Visualizations
- **Google Colab**: Execution environment
