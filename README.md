Predictive Analysis of Amazon Stock Prices Using LSTM
📌 Project Overview

This repository contains my undergraduate thesis project titled "Predictive Analysis of Amazon Stock Prices Using Long Short-Term Memory (LSTM) Model".

The aim of this project is to build a predictive model capable of forecasting Amazon’s stock prices using deep learning techniques. The project applies data preprocessing, exploratory data analysis, and time-series modeling with LSTM to predict daily closing prices.

📊 Dataset

Source: Yahoo Finance API

Ticker: Amazon (AMZN)

Date Range: January 2019 – June 2024

Frequency: Daily stock prices (Open, High, Low, Close, Adj Close, and Volume)

Focus: Prediction of daily closing prices

🔎 Methodology

Data Preprocessing

Cleaning missing and inconsistent values

Normalization for improved model performance

Exploratory Data Analysis (EDA)

Descriptive analytics on stock movement

Visualizations to understand trends, volatility, and correlations

Model Development

Long Short-Term Memory (LSTM) network for time-series forecasting

Training on historical daily closing prices

Model Evaluation
Performance of the model was measured using multiple error metrics:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Mean Absolute Percentage Error (MAPE)

Forecasting

Generated a 30-day prediction of Amazon’s daily closing stock prices

📈 Results

The LSTM model demonstrated the ability to capture trends and patterns in Amazon’s stock price data, producing a 30-day forecast of daily closing prices.

🛠️ Tools & Technologies

Python

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualization

TensorFlow / Keras – LSTM model building

Scikit-learn – Evaluation metrics
