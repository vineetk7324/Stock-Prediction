# Stock Price Prediction using LSTM

This Python program uses LSTM (Long Short-Term Memory) to predict the stock prices of a given company. It fetches historical stock price data using the `yfinance` library, preprocesses the data, and builds an LSTM model to make predictions.

## Prerequisites

Before running the program, make sure you have the required libraries installed:

- numpy
- yfinance
- tensorflow
- scikit-learn
- matplotlib

You can install the libraries using the following command:

## Usage

1. Open the `stock_prediction_lstm.py` file in a code editor.
2. Customize the `ticker_symbol`, `start_date`, `end_date`, `seq_length`, `epochs`, and `batch_size` according to your preferences.
3. Run the program using a Python interpreter:


The program will download the stock price data, preprocess it, train the LSTM model, make predictions, and display a plot showing the actual and predicted stock prices.

Note: This example is for educational purposes and may not result in accurate stock price predictions. Stock price prediction is a complex task and requires thorough research, data analysis, and model tuning for better performance.



