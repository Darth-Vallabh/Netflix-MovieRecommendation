# Netflix-MovieRecommendation
Comparing Netflix movie recommendation techniques
Overview
Netflix Movie Recommendation System

Overview

This project evaluates the effectiveness of three popular recommendation algorithms for Netflix movie recommendations: Singular Value Decomposition (SVD), K-Nearest Neighbors (KNN), and K-Means clustering. The goal is to identify the most effective algorithm for improving recommendation accuracy and user satisfaction. The study includes detailed Exploratory Data Analysis (EDA) to understand user behavior and rating distributions, followed by data preprocessing to handle missing values and normalize ratings.

Each model utilizes a distinct approach:
	•	SVD leverages latent features for accurate predictions but is computationally intensive.
	•	KNN balances simplicity and effectiveness by identifying similar users and movies.
	•	K-Means clusters users/items to enhance diversity in recommendations.

Files

1. EDAMovieRecommendations.ipynb

This notebook includes all Exploratory Data Analysis (EDA) techniques and data preprocessing methods. It handles missing values and normalizes ratings to ensure proper input for the recommendation models.	•	SVD for matrix factorization.

2. KmeansKNN.ipynb

This notebook implements the three recommendation algorithms:
	•	KNN for identifying similar users and items.
	•	K-Means for clustering users/items to enhance diversity in recommendations.

Setup and Execution
	1.	Google Colab Setup:
For the best resources and seamless execution, it is recommended to run the notebooks on Google Colab.
	2.	Running the Code:
Simply run all cells in both notebooks:
	•	EDAMovieRecommendations.ipynb for data preprocessing and EDA.
	•	KmeansKNN.ipunb for model implementation and evaluation.
There are no additional configuration files or run line arguments required.

Requirements
	•	Python 3.x
	•	Libraries:
	•	Pandas for data manipulation
	•	Numpy for numerical operations
	•	Scikit-learn for machine learning models\scikit-surprise
	•	Matplotlib and Seaborn for data visualization

 
