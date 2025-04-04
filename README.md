Restaurant Rating Prediction
This project predicts restaurant ratings based on various features such as city, cost per person, and cuisine types. It aims to help restaurant owners, food aggregators, and investors make informed decisions.

Project Overview
The goal of this project is to develop a machine learning model that predicts restaurant ratings using historical data. The system is designed to be simple and beginner-friendly, with a basic HTML front end and a Flask backend.

Tech Stack
Frontend: HTML (no CSS)

Backend: Flask

Machine Learning: Scikit-learn, Pandas, NumPy

Deployment: Flask server

Dataset
The dataset contains restaurant details such as:

City

Cuisine Types

Cost Per Person

Number of Varieties & Bestsellers

Rating & Category (e.g., Excellent, Good)

Price Category (Affordable, Reasonable, Expensive, etc.)

Features Used for Prediction
Initially, the model is trained using only three input features:

City

Cuisine Types

Cost Per Person

Other features may be included later based on model performance.

How It Works
Data Preprocessing:

Converts categorical features to numerical values using One-Hot Encoding.

Scales numerical features using MinMaxScaler.

Model Training:

Uses Linear Regression (or another regression model) to learn from historical data.

Evaluated using MSE (Mean Squared Error) and R² score.

Prediction Pipeline:

The user enters inputs via a web form.

The backend processes the inputs and predicts the restaurant rating.

The result is displayed in a yellow pop-up box on the webpage.


