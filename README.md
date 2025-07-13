# Forecasting-Toyota-s-Equity-Share-Price-with-LSTM-A-Deep-Learning-Approach

# 📈 Toyota Share Price Forecasting with LSTM

In the fast-paced world of financial markets, predicting equity share prices is a challenging yet valuable task. This project demonstrates how to build a Long Short-Term Memory (LSTM) model using deep learning to forecast the share price of **Toyota Motor Corporation (Ticker: 7203.T)** based on historical data.

## 🚀 Project Overview

* **Objective:** Forecast Toyota’s equity share price using an LSTM network.
* **Approach:** Leverage deep learning to capture non-linear, long-term dependencies in stock price data.
* **Tools:** Python, TensorFlow/Keras, scikit-learn, pandas, matplotlib, yfinance.


## 📒 What’s Inside

* ✅ **Jupyter Notebook:** Fully annotated notebook covering:

  * Data download and preprocessing
  * Train-test split
  * Data scaling with MinMaxScaler
  * LSTM model architecture and training
  * Model evaluation (MAPE, R²)
  * Inverse scaling and visualization of predictions vs. actual prices
* ✅ **Model Architecture:** Stacked LSTM layers with dropout to prevent overfitting.
* ✅ **Optimizer & Loss:** Uses `Nadam` optimizer and `mean_squared_error` loss function for robust regression.

### 📊 website link - https://www.akstats.in/2025/07/forecasting-toyotas-equity-share-price.html

## 🗃️ Data Source

* Historical stock price data is retrieved using [Yahoo Finance](https://finance.yahoo.com/).

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.
Feel free to use, share, or adapt the code for your forecasting tasks.
