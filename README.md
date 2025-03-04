# Time Series Forecasting for Portfolio Management

This project focuses on **time series forecasting** for stock prices using historical financial data. The goal is to predict future stock prices for **TSLA (Tesla)**, **SPY (S&P 500 ETF)**, and **BND (Bond ETF)** to assist in portfolio management decisions.

## Key Features
- **Data Collection**: Historical stock data is downloaded using the `yfinance` library.
- **Exploratory Data Analysis (EDA)**: Visualizations of closing prices, daily returns, and correlation matrices.
- **Forecasting Models**:
  - **SARIMA**: A classical statistical model for time series forecasting.
  - **LSTM**: A deep learning model to capture complex patterns in stock prices.
- **Evaluation**: Performance metrics (MAE, RMSE, MAPE) are calculated to compare model accuracy.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Time-Series-Forecasting-for-Portfolio.git
2. Install the required dependencies:
   pip install -r requirements.txt
3. Run the main script:
   python time_series_forecasting.py
Results
Visualizations: Trends, volatility, and correlations are analyzed.

Forecasts: Predictions for future stock prices with confidence intervals.

Performance: Model accuracy is evaluated using MAE, RMSE, and MAPE.

Dependencies
Python 3.8+

Libraries: yfinance, pandas, numpy, matplotlib, seaborn, statsmodels, pmdarima, tensorflow

---

