# Financial Risk Management

A hands-on exploration of financial risk management techniques, progressing from individual stock analysis through portfolio construction, risk measurement, and time series modeling. Each notebook builds on concepts from the previous ones, forming a coherent learning path through quantitative finance fundamentals.

## Notebooks

### 1. Stock Analysis (`Stock_analysis.ipynb`)

Technical analysis and signal processing applied to individual equities:

- **Charting** -- Candlestick and OHLC charts for price visualization
- **Trend indicators** -- Simple Moving Average (SMA), Exponential Moving Average (EMA), MACD
- **Volatility indicators** -- Bollinger Bands
- **Momentum indicators** -- Fast and slow stochastic oscillators
- **Trend-following** -- Parabolic SAR with backtesting
- **Signal denoising** -- Kalman filter and wavelet transform methods for noise reduction in price series

### 2. Portfolio Analysis (`Portfolio_analysis.ipynb`)

Portfolio construction and performance evaluation:

- Portfolio return and standard deviation computation
- Capital Asset Pricing Model (CAPM)
- Beta estimation
- Risk-adjusted performance metrics: Sharpe ratio, Treynor ratio, Jensen's alpha

### 3. Value at Risk (`VAR.ipynb`)

Risk measurement and fund performance analysis:

- Historical Value at Risk (VaR) estimation
- Historical drawdown analysis
- Fund performance analysis using the ffn library
- Fund rebasing for comparative evaluation

### 4. Time Series Analysis (`Time_series_analysis.ipynb`)

Time series modeling and parametric risk estimation:

- Moving Average (MA), Autoregressive (AR), and ARIMA models
- Parametric VaR (variance-covariance method)
- Empirical VaR

## Tech Stack

- **Python** -- pandas, numpy, scipy, statsmodels
- **Visualization** -- matplotlib, plotly
- **Finance data** -- yfinance, ffn
- **Signal processing** -- PyWavelets
- **Environment** -- Jupyter Notebook

## How to Run

1. Clone the repository and navigate into it:

   ```bash
   git clone <repo-url>
   cd risk-management
   ```

2. Create a virtual environment and install dependencies:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

3. Launch Jupyter and open any notebook:

   ```bash
   jupyter notebook
   ```

   Work through the notebooks in order (Stock Analysis, Portfolio Analysis, VaR, Time Series Analysis) for the intended progression.
