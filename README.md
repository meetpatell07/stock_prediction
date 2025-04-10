# Stock Price Prediction Model

## Overview

This project involves the development of a stock price prediction model using deep learning. The model utilizes historical stock data (Open, Close, High, Low, Volume) to predict whether the stock price will increase or decrease the next day. The primary goal of this project is to leverage machine learning techniques, specifically LSTM (Long Short-Term Memory), to predict stock price movement based on historical data.

## Project Features

- **Data Preprocessing**: The raw stock data is preprocessed by calculating moving averages (SMA) for different periods (5, 20, 50 days).
- **Model Architecture**: The model is built using LSTM (a type of Recurrent Neural Network) and consists of:
  - Two LSTM layers
  - Dropout layers for regularization
  - A fully connected layer
  - A binary output layer predicting whether the price will go up or down
- **Model Training and Evaluation**: The model is trained on historical stock data, and its performance is evaluated on both training and testing sets using accuracy as the primary metric.
- **Prediction**: The trained model is used to predict the price direction for the next day based on the most recent available data.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git
   cd stock-price-prediction
    ```
