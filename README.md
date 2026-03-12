# Spotify-Audio-Intelligence-Synthetic-Music-Analytics-ML
Machine Learning | EDA | Feature Engineering | Clustering | Classification | Regression Dataset: 50,000 synthetic Spotify-style tracks (2000–2024) with 20 genres &amp; 21 audio features
📌 Project Overview

This project performs end-to-end Data Analysis and Machine Learning on a large Spotify-style dataset to understand
how audio features influence genre, mood, and popularity.

The workflow includes:

Data Cleaning & Feature Engineering

Exploratory Data Analysis (EDA)

Correlation & Feature Importance

Genre Classification (Multi-Class ML)

Popularity Prediction (Regression Model)

Mood Clustering using UMAP + KMeans

The goal is to simulate a real-world music analytics pipeline similar to Spotify recommendation systems.

📂 Dataset

50,000 tracks

20 genres

21 audio features

Year range: 2000–2024

Features include:
danceability, energy, loudness, speechiness,
acousticness, instrumentalness, liveness,
valence, tempo, duration_ms, popularity,
genre, year, artist_id, track_id

⚙️ Tech Stack

Python

Pandas / NumPy

Matplotlib / Seaborn

Scikit-learn

XGBoost

LightGBM

UMAP

KMeans

🔍 Project Pipeline
1️⃣ Data Loading & Cleaning

Removed missing values

Converted categorical features

Normalized audio features

2️⃣ Exploratory Data Analysis

Feature distributions

Genre-wise comparisons

Popularity trends

Outlier detection

3️⃣ Correlation Analysis

Heatmap of audio features

Identified strongest predictors of popularity

Feature selection for ML models

4️⃣ Genre Classification (Multi-Class ML)

Model used:

XGBoost Classifier

Tasks:

Predict genre from audio features

Evaluate accuracy, confusion matrix

Feature importance analysis

5️⃣ Popularity Prediction (Regression)

Model used:

LightGBM Regressor

Tasks:

Predict track popularity

Evaluate RMSE / R² score

Identify most influential features

6️⃣ Mood Clustering (Unsupervised Learning)

Techniques:

UMAP (Dimensionality Reduction)

KMeans Clustering

Goal:

Group songs by mood / sound profile

Visualize audio fingerprint clusters

📊 Key Insights

Energy, loudness, and danceability strongly influence popularity

Genres show clear acoustic patterns

Clustering reveals natural mood groups

ML models can predict genre with high accuracy

Popularity prediction works well with tree-based models

📈 Results
Task	Model	Result
Genre Classification	XGBoost	High accuracy
Popularity Prediction	LightGBM	Good R² score
Mood Clustering	UMAP + KMeans	Clear clusters
🚀 How to Run
git clone https://github.com/yourusername/spotify-ml-project
cd spotify-ml-project

pip install -r requirements.txt

jupyter notebook
📌 Skills Demonstrated

Data Cleaning

Exploratory Data Analysis

Feature Engineering

Machine Learning

Classification & Regression

Clustering

Data Visualization

Model Evaluation

⭐ Future Improvements

Deep Learning model

Recommendation system

Streamlit dashboard

Real Spotify API data
