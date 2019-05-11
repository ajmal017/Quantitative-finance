# Quant

## 0. Valuation

a. Black and Scholes world [notebook](https://github.com/0x3W/Quant/blob/master/Black-Scholes%20World.ipynb)
 - European vanilla call option pricing
 - Monte Carlo simulation 
 - Implied volatility surface (smile) calculation
 - AAPL option chain processing from CBOE
 
b. The Cox-Ross-Rubinstein (CRR model) notebook

c. Stochastic Alpha Beta Rho (SABR) model

d. Matrix pricing for illiquid instruments

## 1. Time series analysis & Volatility forecasting

a. Apple Inc (AAPL) stock price [notebook](https://github.com/0x3W/Quant/blob/master/Time-Series%20Forecasting.ipynb)
- Financial returns analysis
- Classical forecasting methods (AR, MA, ARIMA, GARCH)
- Hybrid (classical + deep learning) forecasting methods
 
 ## 2. Data and retrivial
 
a. WebSocket Poloniex BTC/ETH [feed handler](https://github.com/0x3W/Quant/blob/master/Poloniex-BTCETH-SQL-WebSocket-FeedHandler.py) that saves data to flat files, MySQL or kdb+/q database  

b. Apple Inc. (AAPL) [option chain](https://github.com/0x3W/Quant/blob/master/AAPL.dat) from [CBOE](http://www.cboe.com/delayedquote/quote-table) on 14th Nov

c. Bloomberg API [script](https://github.com/0x3W/randomScripts/blob/master/BloombergAPI-SPXmembersHistData.py) that retrives price history of SPX index members

d. Interactive brokers API [script](https://github.com/0x3W/randomScripts/blob/master/IBapi-sample2.R) that retrives historical prices 

e. Wharton Research Data Services [script](https://github.com/0x3W/Quant/blob/master/WRDS.ipynb) for retriving and saving TAQ data
