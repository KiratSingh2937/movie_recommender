# movie_recommender
A content-based movie recommendation system using the TMDB 5000 dataset from Kaggle.
# 🎬 TMDB Movie Recommendation System

This project is a **content-based movie recommender** built using the **TMDB 5000 Movie Dataset**. It recommends similar movies based on genre, cast, keywords, and overview.

## 📁 Files Included

- `movie_recommender_tmdb.ipynb` – the Jupyter Notebook with full code
- `tmdb_5000_movies.csv` – movie metadata
- `tmdb_5000_credits.csv` – credits data (cast and crew)
- `README.md` – project overview

## 🔧 Tools Used

- Python
- pandas, numpy
- scikit-learn
- Jupyter Notebook

## ✅ How It Works

It combines overview, genres, keywords, cast, and director info into a single text field, vectorizes it, and recommends similar movies using cosine similarity.

## 📈 Sample Output

