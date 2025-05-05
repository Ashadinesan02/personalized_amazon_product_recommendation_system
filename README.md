# personalized_amazon_product_recommendation_system

This project is a personalized product recommendation system built using the Amazon Electronics Ratings dataset from Kaggle. It demonstrates my ability to work with real-world datasets, apply machine learning techniques, and build practical recommendation models using Python.

## Why this project?

Recommendation systems are at the heart of platforms like Amazon, Netflix, and Spotify. I chose this project to explore how data science powers real-world personalization. My goal was to build a recommendation engine that evolves from simple popularity-based models to advanced collaborative filtering and matrix factorization techniques — while focusing on performance, accuracy, and user-centric insights.

## Tech Stack and Tools

**Environment** : Google Colab
**Language** : Python
**Libraries** : 
- pandas, numpy - Data handling
- matplotlib, seaborn - Visualization
- scikit-learn - ML utilities
- scikit-surprise - Recommendation algorithms

## Project Workflow

### 1. Data Preparation
- Mounted Google Drive in Colab and loaded the Kaggle dataset.
- Cleaned the dataset: handled missing values, verified data types, filtered users/items.
- Performed exploratory analysis to understand rating distributions and user activity.

### 2. Model Development
- Popularity-Based Model:
  - Based on average rating and number of ratings.
  - The model resulted in a low hit rate and poor personalization.

- Collaborative Filtering (using surprise library):
  - Built both User-User and Item-Item models.
  - Item-Item performed better in terms of RMSE.

- Matrix Factorization:
  - Implemented SVD for better generalization.
  - Achieved the best RMSE of ~0.88 — used for final recommendations.

### 3. Recommendation Output
- Generated product suggestions based on matrix factorization results.
- Model is scalable and can adapt to new user-item interactions.


## Results
- Best Model: Matrix Factorization using SVD
- Performance: RMSE ≈ 0.88
- Insight: Advanced models significantly improve personalization compared to basic popularity-based approaches.

## Getting Started
1. Open the Colab notebook.
2. Mount Google Drive with the dataset.
3. Run the notebook sequentially to see cleaning, modeling, and final recommendations.


## LinkedIn

https://www.linkedin.com/in/asha-d-59026424a





