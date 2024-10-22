## Overview
This project aims to predict **movie ratings** and **revenue** using machine learning models trained on the TMDb and IMDB datasets. It utilizes a structured workflow that includes data collection, preprocessing, model training, and prediction through a user interface and API.

## Features
**Movie Rating Prediction**: Predict the rating of a movie based on its features.
**Revenue Prediction**: Estimate the revenue a movie will generate.
**API Interface**: Built using Flask to handle requests and provide predictions via a RESTful API.
**User Interface**: Command-line-based input for user interaction.

## Technologies Used
Python
Flask (for API)
Machine Learning (Scikit-learn)
Jupyter Notebooks
Pandas & Numpy (for data preprocessing)
Matplotlib & Seaborn (for visualizations)
Pickle (for model serialization)

## Project Structure
├── app.py              # Flask API for handling requests
├── main.ipynb          # Jupyter notebook for data preprocessing and model training
├── tmdb_5000_credits.csv  # Movie credits dataset
├── tmdb_5000_movies.csv   # Movie details dataset
├── IMDB Dataset.csv    # Additional IMDB dataset
├── rating_model.pkl    # Trained model for predicting ratings
├── revenue_model.pkl   # Trained model for predicting revenue
├── class diagram.jpg   # Class diagram for project structure

## usage
This project can be used to:
Predict the success of upcoming movies in terms of ratings and revenue.
Perform exploratory data analysis on movie datasets.
Understand feature importance in movie success.

## Future Work
Extend the prediction models with additional features like actor/crew popularity, genre trends, etc.
Integrate a web-based interface for better user interaction.
Improve model performance by tuning hyperparameters
