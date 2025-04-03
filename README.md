# Movie Recommendation System

## Overview
This project implements a **collaborative filtering recommendation system** using **Singular Value Decomposition (SVD)**. It predicts user preferences and delivers personalized movie recommendations based on historical ratings.

## Dataset
The system uses the following datasets:
- **movies.csv**: Contains movie information, including movie ID, title, and genres.
- **ratings.csv**: Stores user ratings with user ID, movie ID, rating, and timestamp.

## Features
- **Matrix Factorization with SVD**: Decomposes the user-movie rating matrix to predict missing ratings.
- **Personalized Movie Recommendations**: Suggests top-rated movies for a given user based on predicted ratings.
- **Evaluation Metrics**:
  - **Root Mean Square Error (RMSE)** to assess prediction accuracy.

## Usage
To use the recommendation system, follow these steps:
1. Load and preprocess the dataset.
2. Train the model using SVD.
3. Generate personalized movie recommendations.
4. Evaluate the results.
   
## Evaluation
- **RMSE Calculation**: Measures the difference between actual and predicted ratings.
- **Error Distribution Analysis**: Identifies patterns in prediction errors.


