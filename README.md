# Movie_recommendation
This repository contains a collaborative filtering-based movie recommendation system built using Python and popular libraries such as Pandas, NumPy, and Surprise. The project demonstrates how to preprocess datasets, clean data, and implement a recommendation model.

# Project Overview 
Project Overview
The goal of this project is to build a recommendation system that suggests movies to users based on their preferences and past interactions. It involves two main stages:

Data Acquisition and Cleaning:
Cleaning and preprocessing the provided movie and rating datasets.
Recommendation System:
Implementing collaborative filtering to generate movie recommendations.

# Dataset Description
1. movies.csv
Contains details about movies.
Columns include movieId, title, genres, and (optional) poster_path.
2. ratings_cleaned.csv
Contains user ratings for movies.
Columns include userId, movieId, rating, and timestamp.

# Results
The recommendation system predicts top-rated movies for users using collaborative filtering.
Provides accurate suggestions based on user behavior and preferences.

data_acquisition_cleaning.ipynb: To clean the datasets.
recommendation_system.ipynb: To run the recommendation system.


# Dependencies
Python 3.x
pandas
numpy
scikit-learn
surprise
Jupyter Notebook
