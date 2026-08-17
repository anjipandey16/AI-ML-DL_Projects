# Movie Recommender System

A Machine Learning-based Movie Recommender System built using Python and Natural Language Processing (NLP) techniques to suggest similar movies based on content metadata.

## 📌 Project Overview
This project implements a content-based recommendation system that analyzes movie attributes—such as genres, keywords, cast, and crew—to identify patterns and compute similarity scores, generating personalized top movie recommendations for users.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python 3.x
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning & Vectorization:** Scikit-Learn (`CountVectorizer`, `Cosine Similarity`)
* **Environment:** Jupyter Notebook

## ⚡ Pipeline & Implementation
1. **Data Preprocessing:** Cleaned and merged movie metadata, handling missing values and formatting JSON strings into extracted lists.
2. **Feature Extraction:** Combined key textual features (genres, keywords, cast, and crew) into unified tags.
3. **Text Vectorization:** Converted text tags into high-dimensional feature vectors using **CountVectorizer** (bag-of-words model).
4. **Similarity Metric:** Computed pairwise **Cosine Similarity** scores across all vector representations to evaluate content proximity.
5. **Recommendation Engine:** Built a recommendation function that takes a movie title, retrieves its highest similarity scores, and outputs the top 5 most similar movies.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/anjipandey16/AI-ML-DL_Projects.git](https://github.com/anjipandey16/AI-ML-DL_Projects.git)
   cd AI-ML-DL_Projects/Movie_Recommender
