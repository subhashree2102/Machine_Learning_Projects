# Netflix Movie Recommendation System

## Overview
This project implements a Netflix movie recommendation system using Singular Value Decomposition (SVD). The system predicts user ratings and recommends movies based on collaborative filtering techniques.

## Features
- Loads and processes Netflix movie data
- Constructs a user-item rating matrix with sample ratings
- Uses SVD to decompose the rating matrix and extract latent factors
- Predicts ratings based on decomposed matrices
- Recommends top-rated movies for users
- Evaluates accuracy using Mean Squared Error (MSE)

## Usage
1. Load the dataset containing netflix movie data.
2. Generate a random user-item rating matrix.
3. Apply SVD to extract meaningful patterns.
4. Predict user ratings by reconstructing the matrix.
5. Identify and recommend top-rated movies.
6. Evaluate the system using MSE.

## Methodology
- **Data Preprocessing**: The dataset is filtered to include only movies.
- **Matrix Factorization**: SVD is applied to identify latent patterns in ratings.
- **Prediction & Recommendation**: The factorized matrices are used to estimate missing ratings and generate recommendations.
- **Evaluation**: MSE is computed to assess the accuracy of predictions.
