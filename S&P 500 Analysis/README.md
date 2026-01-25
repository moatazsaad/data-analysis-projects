# 📈 Equity Time-Series Analysis of Selected S&P 500 Stocks 

## Overview
This project analyzes historical stock data for major tech companies**Apple (AAPL), Amazon (AMZN), Google (GOOG), and Microsoft (MSFT)** using Python. The focus is on price trends, moving averages, returns, resampling, and correlation analysis.

## Dataset
- Source: `individual_stocks_5yr/`
- Total CSV files: **509**
- Time span: **2013 – 2018**
- Key columns: `date, open, high, low, close, volume, Name`

## Tools & Libraries
- Python, Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Google Colab (Google Drive integration)

## Analysis Performed

### 1. Stock Price Change Over Time
- Visualized closing price trends for AAPL, AMZN, GOOG, MSFT.
- Compared long-term movements across companies.

### 2. Moving Averages
- Calculated **10, 20, 50-day moving averages**.
- Plotted trends to smooth short-term volatility.

### 3. Apple Daily Returns
- Computed daily percentage change in Apple’s closing price.
- Interactive visualization using Plotly.

### 4. Resampling Analysis (Apple)
- Monthly, quarterly, and yearly mean closing prices.
- Identified long-term growth and seasonal patterns.

### 5. Closing Price Correlation
- Compared closing prices across companies.
- Found strong correlations:
  - **MSFT–AMZN (~0.96)**
  - **MSFT–GOOG (~0.91)**

### 6. Daily Returns Correlation
- Analyzed correlation of daily percentage changes.
- Moderate correlation between **AAPL–MSFT** and **AMZN–MSFT**.
- Google showed weak correlation with others.

## Key Insights
- Tech stocks show strong long-term upward trends.
- Moving averages help identify trend direction clearly.
- Closing prices are more correlated than daily returns.
- Daily returns exhibit weaker, more volatile relationships.
