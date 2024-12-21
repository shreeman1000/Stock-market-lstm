# Stock Market Price Prediction with LSTM and Sentiment Analysis
A deep learning model combining LSTM networks and Reddit sentiment analysis for stock price prediction.
## Overview
This project integrates market sentiment data different sources with historical stock data to enhance prediction accuracy. The model analyzes both historical price patterns and public sentiment to forecast stock movements.

## Model Architecture
### Sentiment Analysis

NLTK-based text preprocessing

Trained on 1.6M labeled tweets

82% accuracy on test set

5-day sentiment moving average

### LSTM Network

A simple 2 layer LSTM network

## Performance

RMSE: 11.02

MAE: 8.76

Directional Accuracy: 56.4%

## Features

Historical price data from Yahoo Finance

Real-time Reddit sentiment analysis

Support for major tech stocks (AAPL, AMZN, GOOG, MSFT)

60-day lookback period

Daily price predictions

## Limitations

English-only sentiment analysis

Daily close prices only

Requires active social media presence

Market efficiency assumption
