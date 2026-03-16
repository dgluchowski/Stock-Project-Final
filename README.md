# Stock Price Analysis & Prediction

## Overview
Final project demonstrating end-to-end data science workflow on historical stock data. Includes data collection, exploratory analysis, visualization of trends/volatility, and predictive modeling to forecast price movements.

## Dataset
- Historical stock prices (Open, High, Low, Close, Volume, Adjusted Close)
- Source: Downloaded via yfinance / CSV import
- Time period: [add your dates, e.g., 2015–2025]
- Multiple tickers analyzed for comparison

## Technologies Used
- Python
- Pandas & NumPy (data manipulation & cleaning)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (modeling)
- yfinance (data fetching)

## Methodology
- Data ingestion and preprocessing (handling missing values, feature engineering)
- Exploratory Data Analysis: candlestick charts, moving averages, correlation heatmaps, volatility analysis
- Predictive modeling: [e.g., Linear Regression / ARIMA / LSTM — replace with whatever you used]
- Model evaluation using RMSE, MAE, and R²

## Key Results
- [Add your actual number, e.g., "Achieved R² of 0.89 on test set" or "Predicted next-day price within ±2.3% error"]
- Discovered strong [insight, e.g., "momentum effect in tech stocks" or "volume-price correlation of 0.72"]
- Visualized clear upward/downward trends and seasonal patterns

![Stock Price Prediction](images/prediction_plot.png)
![EDA Visualization](images/candlestick.png)

## How to Run
```bash
git clone https://github.com/WhatAmIDoingYo/Stock-Project-Final.git
cd Stock-Project-Final
pip install -r requirements.txt
python Final_Project.py
