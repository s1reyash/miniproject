# Stock Forecasting Mini Project

A Python mini project for exploring stock-price time series and forecasting views. It includes data-preparation code, a sample Microsoft dataset, local model artefacts, and a Streamlit interface.

## What it includes

- `micro.py` prepares time-series windows and training, validation, and test splits
- `mini.py` provides a Streamlit forecasting interface
- The dashboard retrieves selected market data with yfinance and displays Prophet forecasts with Plotly charts

## Run locally

Install the Python dependencies, including Streamlit, yfinance, Plotly, Pandas, and a compatible Prophet package, then run:

```bash
streamlit run mini.py
```

## Disclaimer

This project is for learning and visualisation. Forecasts are not investment advice and should not be used as the sole basis for financial decisions.
