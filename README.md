# Time Series Forecasting

This repo is used to learn about the fbprophet module used to predict future values.
There are two files in this repo, the first one is about an item value with the provided dataset then the second one is about cryptocurrency. Cryptocurrencies can be replaced with stocks using the yfinance module.

## FbProphet

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

### How to Install FbProphet
```sh
conda install -c conda-forge fbprophet
```
I suggest you to install FbProphet via Anaconda Prompt because if it is installed in the Jupyter Notebook kernel, it will take longer.
