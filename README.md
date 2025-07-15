# 🎬 Movie Recommendation System

This project is an AI-powered **Movie Recommendation System** built from scratch using Python. It includes two major techniques:

- **Content-Based Filtering**: Recommends movies based on movie descriptions (e.g., genres, plots, language).
- **Collaborative Filtering**: Recommends movies based on user behavior and preferences using **Matrix Factorization (SVD)**.

---

## 📁 Dataset

- Custom-built dataset including 100+ movies from **Hollywood**, **Bollywood**, **Sandalwood**, **Tollywood**, and **Kollywood**.
- Contains:
  - `movies.csv`: Movie ID, Title, Genres, Language
  - `ratings.csv`: User ID, Movie ID, Ratings, Timestamp

---

## 🧠 Techniques Used

### 1. Content-Based Filtering
- Used **TF-IDF Vectorization** to extract keyword importance from movie descriptions.
- Used **Cosine Similarity** to find similar movies based on those vectors.

### 2. Collaborative Filtering
- Used the **Surprise** library
- Applied **SVD (Singular Value Decomposition)** for matrix factorization
- Evaluated using **RMSE** and **MAE**

---

## 📌 Requirements

- Python 3.x
- pandas
- scikit-learn
- scikit-surprise (for collaborative filtering)
- Jupyter Notebook or Google Colab

   
