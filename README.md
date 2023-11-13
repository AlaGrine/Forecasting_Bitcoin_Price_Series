# Forecasting Bitcoin closing price series

## Time series forecasting

<div align="center">
  <img src="https://github.com/AlaGrine/Forecasting_Bitcoin_Price_Series/blob/main/stats/BTC_logo2.jpg" >
</div>

### Table of Contents

1. [Project Overview](#overview)
2. [Installation](#installation)
3. [File Descriptions](#file_descriptions)
4. [Approaches to Bitcoin price forecasting](#modelling)
5. [Results](#results)
6. [Acknowledgements](#Acknowledgements)

## Project Overview <a name="overview"></a>

Time series forecasting is one of the most widely used data science techniques in business and finance to make future strategic decisions.

The aim of this project is to forecast the daily closing price series of [Bitcoin](https://coinmarketcap.com/currencies/bitcoin/), a peer-to-peer online currency, using the historical price of Bitcoin.

I followed different approaches to time series forecasting, implementing both statistical techniques and machine learning algorithms.

I used classical approaches to time series forecasting, such as exponential smoothing and ARIMA, and I leveraged Tensorflow to build a variety of artificial neural networks (including linear, CNN and RNN models) with multivariate time series.

## Installation <a name="installation"></a>

This project requires Python 3 and the following Python libraries installed:

`yfinance`, `pandas`, `numpy`, `tensorflow` , `pmdarima`, `statsmodel`, `matplotlib`, `plotly` and `googletrans`

## File Descriptions <a name="file_descriptions"></a>

The main file of the project is `BTC_forecast.ipynb`: the source code.

The project folder also contains the `stats` folderwhich contains the evaluation metrics for all models (.CSV files).

## Approaches to Bitcoin price forecasting <a name="models"></a>

I built the following models:

1. Baseline: Naive Bayes.
2. Simple Moving average (SMA).
3. Exponontiel Smoothing: SES and Holt.
4. ARIMA model with [pmdarima](http://alkaline-ml.com/pmdarima/).
5. Deep learning models with [Tensorflow](https://www.tensorflow.org/): Dense, LSTM, GRU and Conv1D.

## Results<a name="results"></a>

I wrote a blog post about this project. You can find it [here](https://alagrine.github.io/post/p6-bitcoin_price_forecast/).

## Acknowledgements <a name="Acknowledgements"></a>

Must give credit to [yfinance](https://pypi.org/project/yfinance/) for the dataset.
