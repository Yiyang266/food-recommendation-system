# Food Recommendation System (Graph-Based)

This project is an independent exploratory program I developed based on my interest in recommendation systems, using user preference data and text-based feature engineering.

## Overview

The goal is to recommend new food items to users based on similarity in preferences.  
The system transforms categorical food choices into text-like features and applies machine learning techniques.

## Methods

- Text preprocessing and keyword extraction  
- TF-IDF vectorization  
- Dimensionality reduction using SVD  
- Similarity-based recommendation (cosine similarity)  
- Graph construction using similarity matrix  
- Community detection using graph clustering  
- Ranking using PageRank algorithm  

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

## Notes

This project explores how graph-based methods can capture deeper relationships between items compared to traditional collaborative filtering approaches. 

One challenge encountered was handling real-world text data, including extracting relevant food-related keywords and constructing a consistent feature matrix.

