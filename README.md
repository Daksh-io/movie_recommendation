# 🎬 Movie Recommendation System

A full-stack movie recommendation web application that allows users to search for movies, explore details, and discover similar films using intelligent recommendations.

---

## This project combines:

🧠 A Machine Learning similarity model (TF-IDF)

🌐 Real-time movie data from TMDB

⚡ FastAPI backend (API layer)

🎨 Streamlit frontend (User Interface)

---

## 🚀 Live Concept Overview

This system works like a mini Netflix-style explorer:

User searches for a movie

The system fetches official data (poster, rating, overview)

The system generates:

🔎 Content-based similar movies

🎭 Genre-based recommendations

---

## 🧠 How Recommendations Work

### 1 Content-Based Filtering (TF-IDF)

Analyzes movie descriptions.

Converts text into numerical vectors.

Uses cosine similarity to find related movies.

Recommends movies with similar themes.

Example:
If you search "Batman", you may get:

Dark superhero movies

Action thrillers

DC universe films

---

### 2 Genre-Based Recommendations

Extracts the movie's main genre.

Fetches popular movies from the same genre using TMDB.

Provides broader suggestions within the same category.

---

## 🛠️Tech Stack:

Pandas/Numpy

Scikit-learn 

FastAPI

Streamlit

TMDB API

---

# 📌 Summary (In One Paragraph)

This project is a smart movie recommendation web application that allows users to search for movies, view detailed information, and receive personalized recommendations. It combines a machine learning similarity model (TF-IDF) with real-time movie data from TMDB. The backend is built with FastAPI, and the user interface is built with Streamlit, creating a complete full-stack AI-powered application.
