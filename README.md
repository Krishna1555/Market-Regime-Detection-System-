
# Market Regime Detection System

A Python project that analyzes stock market data and identifies different market conditions: Bull, Bear, and Sideways.

## About the Project

This project uses historical stock prices to understand how the market behaves in different conditions. It calculates indicators like volatility, moving averages, and RSI, then uses machine learning to group market data into different regimes.

The results are shown in a chart, making it easier to see how market conditions change over time.

## Features

- Downloads historical stock data using Yahoo Finance.
- Calculates volatility, moving averages, and RSI.
- Uses KMeans clustering to identify market regimes.
- Identifies Bull, Bear, and Sideways market conditions.
- Visualizes stock prices and detected regimes on a chart.

## Tech Stack

- Python
- Pandas
- NumPy
- yfinance
- Scikit-learn
- Matplotlib

## Project Structure

- `main.py` – Runs the project and displays the results.
- `regime_model.py` – Handles feature engineering and regime detection.
- `requirements.txt` – Contains the required Python packages.
- `README.md` – Project documentation.

## How to Run

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

## What I Learned

- Working with historical stock market data.
- Calculating technical indicators.
- Using KMeans clustering for market analysis.
- Understanding different market conditions.
- Visualizing financial data using Python.
