# Disney (DIS) Stock Forecasting using SARIMAX

## Project Overview

This project focuses on building a SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables) model to forecast the daily closing price of **The Walt Disney Company (DIS)** stock.

### Why SARIMAX?

SARIMAX is well-suited for time series forecasting with:
- Trends or seasonality
- External regressors (volume, market index, etc.)
- Financial data that shows autocorrelation and non-stationarity

---

## Objectives

- Load and clean daily historical stock price data for DIS
- Explore trends, stationarity, and volatility
- Perform seasonal decomposition
- Fit and tune a SARIMAX model
- Forecast future prices and visualize confidence intervals
- 

---

## Dataset

**Source:** Kaggle / Yahoo Finance / Local CSV  
**File used:** `sp500_stocks.csv`  
**Filtered Ticker:** `DIS`  
**Date Range:** 2010 to 2024  
**Frequency:** Daily

---

## Tech Stack

- Python
- pandas, numpy
- matplotlib, seaborn
- statsmodels
- pmdarima (for auto_arima)

---

## Structure

```plaintext
📁 sp500-stock-forecasting/
├── .gitignore
├── README.md
├── sp500_stocks.csv
├── notebooks/
│   └── dis_forecasting.ipynb

