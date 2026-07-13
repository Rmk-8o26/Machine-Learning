# Granger Causality Test — Stock Prices

Perform **Granger Causality tests** among Apple (AAPL), Walmart (WMT), and Tesla (TSLA) stock prices to determine if one stock's price predicts another.

## Pipeline
- Stationarity tests: ADF (Augmented Dickey-Fuller) and KPSS
- Vector Autoregression (VAR) model
- Granger causality tests
- Model evaluation: RMSE, MAE, Durbin-Watson

## Datasets
- `AAPL.csv`, `WMT.csv`, `TSLA.csv` — daily OHLCV stock data (~2,638 rows each)

## Requirements
```
pip install -r requirements.txt
```
