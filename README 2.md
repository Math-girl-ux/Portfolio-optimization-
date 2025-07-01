
# Portfolio Optimization using Sharpe Ratio (Tech Stocks)

## Overview

This project demonstrates how to optimize a stock portfolio using the **Sharpe Ratio**. We simulate 10,000 random portfolios of major US tech stocks and identify the one with the best return-to-risk balance.

## Data Source

- Yahoo Finance (`yfinance`)
- Stocks used: AAPL, MSFT, GOOGL, TSLA, AMZN, NVDA
- Date range: 2019-01-01 to 2024-12-31

## Tools Used

- Python
- pandas, numpy, matplotlib
- scipy.optimize
- yfinance

## Process

- Download historical data
- Calculate returns
- Simulate random portfolios
- Calculate returns, risk, and Sharpe ratio
- Visualize portfolios and find the optimal one

## Output

- Optimal portfolio weights
- Best Sharpe Ratio
- Portfolio return and volatility
- Scatter plot of 10,000 portfolios

## How to Run

1. Install dependencies with `pip install -r requirements.txt`
2. Run `Portfolio_Optimization.ipynb` in Jupyter or Colab

## Author

Vanessa Chinhengo
