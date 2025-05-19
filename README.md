# ICBC Stock Price Analysis and Forecasting (January 2020 - June 2024)

### Author: Zhengling Jiang

## Summary
Industrial and Commercial Bank of China (ICBC) is one of the world’s largest commercial banks and a key player in China’s financial system. In this project, we analyze ICBC's A-share stock price performance from January 2020 to June 2024 and build a predictive model to forecast future prices using deep learning.

Our goal is to explore the historical trends in ICBC's stock price by analyzing its price trends, distribution of daily returns, and trading volume. We then conduct a risk analysis by visualizing volatility and calculating Value at Risk (VaR). Finally, we forecast future prices using a Long Short-Term Memory (LSTM) neural network.

### Report

You can find the full project report [here](https://github.com/ClaireJ2100/icbc-stock-financial-analysis/blob/main/icbc-stock.pdf).

## Project Highlights
- **Data Collection**: Retrieved daily ICBC A-share price data using the `akshare` package.
- **Exploratory Data Analysis**:
  - Visualized price trends and moving averages (30-day, 90-day).
  - Analyzed daily returns, volatility, and trading volume.
- **Risk Analysis**:
  - Calculated 30-day rolling volatility.
  - Etimated Value at Risk (VaR) at 95% and 99% confidence intervals.
- **Stock Price Forecasting**
  - Built and tuned an LSTM neural network to forecast future closing prices.
  - Applied Keras Tuner for hyperparameter optimization.
- **Model Evaluation**:
  - Evaluated model performance using four standard regression metrics:
    - Root Mean Squared Error (RMSE): 0.0674  
    - Mean Absolute Error (MAE): 0.0546  
    - $R^2$ Score: 0.9583  
    - Mean Absolute Percentage Error (MAPE): 1.06%
  - Visualized predicted vs. actual prices.

## Key Takeaways
While stock price prediction models based solely on historical prices have limited predictive power in practice, this project demonstrates:
- Real-world financial data handling.
- Time series forecasting techniques.


## Usage

1. Clone the repository
```bash
   git clone https://github.com/yourusername/icbc-stock-financial-analysis.git
```
2. Set up environment
```bash
conda env create -f environment.yml
conda activate icbc-stock
```
## License
This project is for educational and portfolio purposes. It is licensed under the terms of the MIT license.


