# Food Recommendation System (Graph-Based)

This project is an independent exploratory program I developed based on my interest in recommendation systems, using user preference data and text-based feature engineering.

## Overview

The goal is to recommend new food items to users based on similarity in preferences.  
The system transforms categorical food choices into text-like features and applies machine learning techniques.

## Methods

- Data preprocessing using pandas
- Feature encoding (one-hot encoding)
- Text vectorization using TF-IDF
- Dimensionality reduction using Truncated SVD
- Similarity computation using cosine similarity
- Recommendation based on similar users

## Workflow

1. Load and preprocess user preference data  
2. Convert features into text format  
3. Apply TF-IDF vectorization  
4. Reduce dimensionality (SVD)  
5. Compute similarity between users  
6. Recommend new items based on similar users  

## Tools

- Python  
- pandas  
- scikit-learn  

## Example Output

The model identifies users with similar preferences and recommends new food items that the target user has not tried.

