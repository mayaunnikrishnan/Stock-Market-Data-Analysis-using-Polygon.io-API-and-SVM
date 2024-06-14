# Stock Market Data Analysis using Polygon.io API and SVM

This project scrapes historical stock price data from the Polygon.io API, preprocesses the data, and performs time series analysis using Support Vector Machines (SVM).

## Table of Contents

- [Overview](#overview)
- [Data Collection](#data-collection)
- [Data Preparation](#data-preparation)
- [Model Development](#model-development)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [Results](#results)


## Overview

The objective of this project is to demonstrate how to scrape stock market data from Polygon.io, preprocess the data, and use an SVM model for time series analysis to predict stock prices. The project includes data collection, preprocessing, model training, evaluation, and visualization.

## Data Collection
The script collects historical stock price data for a specified stock (AAPL in this example) from the Polygon.io API. The data includes dates and closing prices.

## Data Preparation
- The collected data is stored in a Pandas DataFrame.
- Additional features such as percentage price change and moving averages are created.
- The data is preprocessed by handling missing values and splitting it into training and test sets.
## Model Development
- An SVM model (SVR from scikit-learn) is implemented to perform time series analysis.
- The features are scaled using StandardScaler for standardization.
- The model is trained on the training data.
## Evaluation
- The model's performance is evaluated using Mean Squared Error (MSE).
- Predictions are made on the test set to compare actual vs. predicted stock prices.
## Visualization
- A plot is generated to visualize the actual and predicted stock prices over time.
## Results
- The model's performance is summarized using MSE and a plot showing the actual vs. predicted stock prices.
