# Overview

This project builds a Hybrid Recommender System that combines:

Collaborative Filtering (SVD) — learns from user–item interactions (ratings).

Content-Based Filtering (TF-IDF) — analyzes book metadata (titles, authors, and text similarity).

By blending these two techniques, we generate personalized and explainable book recommendations that balance both user preferences and book similarities.


# Features

 Collaborative Filtering using Surprise SVD

 Content-based Filtering using TF-IDF on metadata

 Hybrid Scoring — combines SVD predictions with TF-IDF similarity

 Model Evaluation (RMSE, MAE, Precision@K)

 Interactive Gradio App — explore recommendations dynamically

 User Feedback Loop (fine-tuning recommendations)

 Result Comparison Dashboard


  # App Preview

Input:

User ID

Book Title 

Output:
Top 5 recommended books with:

Predicted rating (SVD)

Average rating

Author

Similarity score (TF-IDF)

# app link
