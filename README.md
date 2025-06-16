# Movie-Recommender-System
A collaborative filtering movie recommender system built with Python, Pandas, and Scikit-surprise
Project Title: Personalized Movie Recommender System

Project Objective:

To build a personalized movie recommendation engine that predicts a user's rating for a given movie. This project demonstrates an understanding of collaborative filtering, a fundamental technique behind modern personalization services like Netflix and Spotify.

Methodology & Key Skills:

Data Handling: Loaded and processed the MovieLens 100k dataset using Python and the Pandas library.
Collaborative Filtering Model: Implemented a Singular Value Decomposition (SVD) matrix factorization model using the scikit-surprise library. SVD is an advanced algorithm that uncovers latent factors (hidden patterns) in user-item interactions.
Model Training & Evaluation:
Split the data into an 80% training set and a 20% testing set to ensure robust evaluation.
Trained the SVD model on the training data to learn user preferences and movie characteristics.
Evaluated the model's performance on the unseen test set using the Root Mean Squared Error (RMSE) metric.
Prediction: Built a function to predict a specific user's potential rating for a movie they have not yet seen.
Key Achievements & Results:

Achieved a strong RMSE of 0.8807 on the test set, indicating that the model's predictions are, on average, less than one star away from the user's true rating on a 5-star scale.
Successfully deployed the model to generate personalized predictions, such as estimating that a sample user would rate "The Dark Knight, The (2008)" at 4.10 stars.
This project demonstrates the ability to build and evaluate a practical, end-to-end machine learning system for personalization at scale.
Technologies Used:

Python
Pandas
Scikit-surprise
SVD (Singular Value Decomposition)
Machine Learning (Recommender Systems, Collaborative Filtering)
