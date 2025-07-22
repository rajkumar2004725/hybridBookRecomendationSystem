# 📚 Hybrid Book Recommendation System

This project is a **Hybrid Book Recommendation System** built using Python. It combines **content-based filtering** and **collaborative filtering** to recommend books based on user preferences and similarities.

## 🧠 How It Works

1. **Data Preprocessing**
   - Merges data from multiple CSV files (`Books`, `Users`, and `Ratings`)
   - Cleans and filters data for consistent formatting

2. **Collaborative Filtering**
   - Constructs a **user-item rating matrix**
   - Uses cosine similarity to find similar users
   - Recommends books based on ratings from similar users

3. **Content-Based Filtering**
   - Extracts metadata like book title and author
   - Computes **TF-IDF vectors** on book descriptions/titles
   - Recommends books similar in content to user preferences

4. **Hybrid Approach**
   - Combines both filtering methods to produce better, more accurate recommendations

## 🔧 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- Cosine Similarity (from `sklearn.metrics.pairwise`)
- Jupyter Notebook

## 📁 Dataset

The dataset includes:
- `Books.csv`: Book metadata (title, author, etc.)
- `Users.csv`: User demographic data
- `Ratings.csv`: User ratings for books

## 📌 Features

- Shows top-rated books
- Handles sparse matrix with collaborative filtering
- Generates book suggestions based on:
  - Similar user preferences
  - Similar content
- Clean and reproducible pipeline

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/rajkumar2004725/hybridBookRecomendationSystem.git
   cd hybridBookRecomendationSystem
