# 🎬 Movie Recommendation System - Content-Based Filtering

This project demonstrates a machine learning workflow to build a **Content-Based Recommendation System** using the [MovieLens Small Dataset](https://grouplens.org/datasets/movielens). It includes both **data analysis** and a **modeling approach** for personalized movie suggestions.

## 📌 Problem Statement

With an ever-growing pool of content, it's important to help users discover movies aligned with their tastes. Content-based filtering enables recommendations based on item metadata like genre, description, or keywords.

## 📊 Dataset

We use the MovieLens 100K dataset containing:
- **100,000+ ratings** by **600 users**
- **~9,700 movies** with genres and titles

Files used:
- `ratings.csv`
- `movies.csv`

## 🧠 Approach

1. **Data Cleaning & EDA**  
   Understand user behavior and genre trends through exploratory analysis.

2. **Feature Engineering**  
   - Text processing of genres and movie titles
   - Vectorization using TF-IDF to quantify movie metadata

3. **Modeling: Content-Based Filtering**  
   - Cosine similarity between movie vectors
   - Top-N recommendation based on similarity scores

4. **Evaluation**  
   - Sample user input
   - Recommended movie list and their metadata

## 📈 Key Results

- Created a lightweight recommender system using metadata only (no user history needed).
- Produced relevant and diverse suggestions based on movie content.

## 🛠️ Technologies

- Python, Pandas, NumPy
- Scikit-learn (TF-IDF Vectorizer, cosine similarity)
- Matplotlib & Seaborn for visualizations

## 🚀 Run it yourself

1. Clone the repo  
   ```bash
   git clone https://github.com/<your-username>/movie-recommender-content-based.git
   cd movie-recommender-content-based
