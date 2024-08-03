# Stock Price Prediction Using LSTM

This project is a practice exercise in building and deploying a machine learning model to predict stock prices using Long Short-Term Memory (LSTM) networks. It aims to explore how LSTMs can capture temporal patterns in financial time series data and provide forecasts for stock price movements.

## Project Overview

The project involves downloading historical stock price data, preprocessing it for training, and using an LSTM model to make predictions. The model is then evaluated on its ability to forecast future stock prices.

## Features

- **Data Retrieval:** Utilizes the `yfinance` library to download historical stock data for multiple companies.
- **Data Preprocessing:** Scales data and prepares it for LSTM training by creating time series sequences.
- **Model Training:** Implements a neural network using LSTM layers to learn patterns from historical data.
- **Forecasting:** Predicts future stock prices and visualizes them against actual prices.
- **Evaluation:** Computes error metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE) to assess model performance.

## Getting Started

### Prerequisites

- Python 3.7 or later
- Required Python packages:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `yfinance`
  - `scikit-learn`
  - `tensorflow`

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/zym-starx/stock-price-prediction.git
   cd stock-price-prediction
