# Graph-Based Analysis of Food Preferences for Recommendation

This project is an independent exploratory program I developed based on my interest in recommendation systems, using user preference data and text-based feature engineering.

## Overview

This project explores how graph-based methods can be used to analyze user food preferences and uncover underlying structure in text-based data.

Rather than directly predicting recommendations, the goal is to represent user preferences, identify similarity between users, and organize them into meaningful groups that can support recommendation tasks.

## Methods

- Text preprocessing and keyword extraction  
- TF-IDF vectorization  
- Dimensionality reduction using SVD  
- Similarity-based recommendation (cosine similarity)  
- Graph construction using similarity matrix  
- Community detection using graph clustering  
- Ranking using PageRank algorithm  

## Workflow

1. Construct a small dataset of food preference texts
2. Convert text into TF-IDF feature vectors
3. Compute pairwise similarity between documents
4. Build a k-nearest neighbor graph
5. Detect communities of similar preferences
6. Rank central nodes within the graph using PageRank

## Results

The results show that similar food preferences are grouped into distinct communities, such as meat-based, seafood-based, and mixed or Asian-style preferences.

Within each community, PageRank identifies the most central and representative documents, which can be interpreted as typical examples of that preference group.

## Tools

- Python  
- pandas  
- scikit-learn  

## Notes

This project highlights the importance of feature representation in text-based systems. While the dataset here is synthetic and simplified, the approach can be extended to real-world data with more advanced text preprocessing and larger-scale modeling.
