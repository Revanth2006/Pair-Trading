# Pair-Trading
This project implements a pair trading strategy using historical stock data.

## 📚 Strategy Overview
- Pairs Trading via z-score on spread
- Entry: z > 1 or z < -1
- Exit: -0.5 < z < 0.5

## ⚙️ Technologies Used
- Python (Pandas, NumPy, matplotlib)
- Yahoo Finance API (`yfinance`)
- statsmodels (cointegration test, regression)
