# 🎬 Movie Recommendation System

This project implements a **Content-Based Movie Recommendation System** using cosine similarity on movie metadata. Given a movie name, it suggests similar movies based on features like genres, keywords, cast, and more.

---

## 🚀 Features

- Content-based filtering using cosine similarity
- Movie suggestions based on description and cast
- Clean and simple logic in a Jupyter Notebook
- Uses publicly available movie metadata
- Lightweight and fast, ideal for learning or enhancement

---

## 📦 Dataset

you can find on repositry



---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📷 Output Screenshots

you can find on repositry
---

## 🎥 Demo

you can find on repositry

---

## 🧠 How It Works

1. Combine important features from both CSVs (`movies.csv`, `credits.csv`)
2. Clean and process textual data (cast, keywords, genres)
3. Convert all important info into a single "tags" column
4. Use **CountVectorizer** to convert text to vectors
5. Apply **Cosine Similarity** to compute similarity scores
6. Recommend top N similar movies based on a given movie

---
