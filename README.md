# 🎬 Movie Recommendation System

This project is a hybrid **Movie Recommendation System** built using machine learning and natural language processing techniques. It leverages both **content-based filtering** and **collaborative filtering** to provide smarter, sentiment-aware movie recommendations.

## 📌 Overview

The system uses metadata and credits from the TMDB 5000 dataset to recommend movies. It integrates:
- TF-IDF vectorization of movie overviews
- Cosine similarity for content-based filtering
- TruncatedSVD for collaborative filtering simulation
- Sentiment-based rating adjustment for enhanced recommendations

## 🚀 Features

- ✅ Preprocessing of movie and credit data
- ✅ Content-based recommendation using NLP
- ✅ Collaborative filtering using matrix factorization
- ✅ Sentiment adjustment to refine ratings
- ✅ Interactive visualizations using Plotly and Seaborn

## 🧰 Technologies & Skills Used

- **Programming:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Machine Learning:** Scikit-learn (TruncatedSVD, SelectKBest, f_regression)
- **NLP:** TF-IDF Vectorizer, Sentiment-aware overview processing
- **Recommendation Techniques:** Content-based filtering, Collaborative filtering, Cosine similarity
- **Data Preprocessing:** MinMaxScaler, Feature selection

## 📊 Dataset

- [TMDB 5000 Movies Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Contains:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

## 📈 Visualizations

- Correlation plots between features and ratings
- Sentiment-adjusted vs original ratings comparison
- Heatmaps and feature importance scores


