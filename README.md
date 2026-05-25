# Stock Market Analysis and Prediction

## Project Overview
This project focuses on analyzing historical stock market data and building deep learning models to predict stock price movements. The analysis uses Apple Inc. (AAPL) stock data to explore market trends, volatility, and forecasting techniques using LSTM and CNN architectures.

## Business Problem
Stock markets are highly volatile and influenced by multiple economic and behavioral factors. Accurate forecasting models can help investors and analysts make data-driven financial decisions and improve short-term trading strategies.

## Objectives
- Analyze historical stock market trends and volatility
- Build deep learning models for stock price prediction
- Compare model performance across different architectures
- Visualize market behavior and prediction accuracy
- Evaluate the effectiveness of technical indicators

## Dataset
**Source:** Kaggle – NASDAQ Stock Dataset

### Dataset Details
- Apple Inc. (AAPL) stock data
- Historical data from 1980–2020
- 40 years of trading records

### Features Used
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close
- Trading Volume

## Tools & Technologies
- Python
- Pandas & NumPy
- TensorFlow / Keras
- LSTM & CNN Models
- Scikit-learn
- Matplotlib
- Seaborn

## Methodology

### Data Preparation
- Cleaned and validated historical stock data
- Handled missing values using backfill methods
- Applied MinMaxScaler normalization

### Feature Engineering
Created technical indicators including:
- 50-Day Moving Average (MA50)
- 200-Day Moving Average (MA200)
- Daily Price Change %
- Previous Day Closing Price

### Model Development
Implemented:
- LSTM Model
- CNN Model
- Hybrid LSTM + CNN Architecture

### Model Evaluation
Models were evaluated using:
- RMSE (Root Mean Squared Error)
- Training Loss
- Validation Loss

## Model Performance

### Best Model: Hybrid LSTM + CNN
- **Training Loss:** 2.07e-05
- **Validation Loss:** 0.00087
- **RMSE:** 138.05
- **Best Epochs:** 15

## Key Insights
- LSTM + CNN models performed effectively for time-series forecasting
- Moving averages improved trend detection accuracy
- Predictions were strongest during stable market conditions
- Model performance declined slightly during highly volatile periods

## Visualizations
The project includes visual analysis of:
- Historical stock price trends
- Market volatility
- Technical indicators
- Actual vs Predicted stock prices
- Moving average analysis

## Future Improvements
- Integrate news sentiment analysis
- Build real-time prediction pipelines
- Explore ensemble forecasting techniques
- Deploy prediction models as web applications

## Conclusion
This project demonstrates how deep learning models such as LSTM and CNN can be applied to financial time-series forecasting. By combining technical indicators with neural network architectures, the analysis provides meaningful insights into stock market behavior and predictive modeling performance.
