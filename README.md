# 📊 Stock Data Analysis Experiments in Python

This repository contains **22 Python experiments** for analyzing stock market data using **pure Python**, `pandas`, `matplotlib`, and `numpy`. No machine learning libraries like `scikit-learn` or `statsmodels` are used, making this project lightweight, transparent, and easy to follow for beginners and intermediates.

---

## 📁 Dataset

The project uses a CSV file with columns:

- `Ticker`
- `Date`
- `Open`, `High`, `Low`, `Close`
- `Adj Close`
- `Volume`

---

## 🧪 Experiments Included

### 📈 Price and Trend Analysis
1. Plot Closing Price Over Time  
2. Calculate and Plot Moving Averages (20 & 50 days)  
3. Calculate Daily Returns (%)  
4. Plot Histogram of Daily Returns  
5. Cumulative Returns Over Time  
6. Exponential Moving Average (EMA)  
7. Bollinger Bands  
8. Trend Detection Using Manual Linear Regression  
9. Golden Cross & Death Cross  
10. Manual Forecasting Using Simple Moving Average  

---

### 🔎 Statistical Analysis
11. Volatility (Standard Deviation of Daily Returns)  
12. Autocorrelation Plot of Daily Returns  
13. Sharpe Ratio Calculation (manual)  
14. Identify Outliers in Daily Returns  

---

### 📊 Technical Indicators
15. Relative Strength Index (RSI)  
16. Moving Average Convergence Divergence (MACD)  

---

### 📉 Price Behavior Visualization
17. Candlestick Chart using `mplfinance`  
18. Correlation Heatmap Between Tickers (if multiple tickers)  

---

### 🔍 Clustering & Classification
19. Manual Rule-Based Clustering by Daily Return  
20. Volume vs Return Scatter Plot by Cluster  

---

### 🔮 Forecasting (Manual)
21. Simple Moving Average (SMA) Forecast  
22. Linear Regression-Based Trend Forecast (Manual Calculation)

---

## 🛠 Requirements

```bash
pip install pandas matplotlib numpy mplfinance seaborn
