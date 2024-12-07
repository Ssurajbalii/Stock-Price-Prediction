# Stock Price Prediction

## Introduction

This project, part of **COMP-3704 Neural Networks and Deep Learning, Fall 2024 at Red River College Polytechnic**, focuses on predicting stock prices and trading signals using advanced machine learning techniques. The volatile nature of financial markets makes stock price forecasting a complex task.

The project employs **LSTM models** for sequential data analysis, the **N-BEATS algorithm** for advanced time series forecasting, and integrates **technical indicators** like EMA and RSI to enhance predictions. Additionally, it explores sentiment analysis of Elon Musk's tweets to identify potential correlations with stock price movements.

The goal is to combine historical data, technical indicators, and sentiment features to improve stock trend prediction and support informed decision-making.



## Stages
1. **Stage I**: LSTM Models
   - Experiments with Single Layer, Stacked, and Bidirectional LSTMs.
   - Overfitting addressed using regularization and dropout.

2. **Stage II**: Sentiment Analysis
   - Analyzed Elon Musk’s tweets (2010–2023) with TextBlob. Found no correlation with stock prices.

3. **Stage III**: Signal Prediction with LSTM and Using N-BEATS for price prediction
   - Added technical indicators (EMA, RSI, MACD, Bollinger Bands).
   - Predicted buy/sell signals, not prices.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/stock-price-prediction.git
   cd stock-price-prediction

2. Install the requirements
   ```bash
   pip install -r requirements.txt

