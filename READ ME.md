# <center> Time Series Forecasting in Real Estate Valuation  </center>


## Problem Statment

In the past years real estate Trades Prices in Japan's have been rising up and down,affected by the
economic market. The main challenge here is to determine the future value of the property after a certain period of time, taking into account various expected factors such as the effects of the current pandemic to the future results.

We will build a time series forecasting model to forecast the property average prices based on historical data of all the 47 prefectures in Japan. Using time series Algorithms will help us to understand the characteristics and the
statistics of the real estate data. 

## Project Guideline: 


This work is organize to 3 notebook files:

**Notebook 1: EDA & Feature Engineering.**<br>
**Notebook 2: Static Modeling for Producing Time Series.**<br>
**Notebook 2: Mean-Point Time Series Modeling.**<br>


using Tokyo prefecture data provided by by Ministry of Land, Infrastructure, Transport and Tourism of Japan (MLIT) with addition to the housing consumer price index for japan data, we introduce two approaches:

**First Static Modeling for Producing Time Series:**

For every quarter we produced static models. Then predict the price of an instance, using all quarter models. The result is a predicted time series data which will then be forecasted into the future using an **LSTM** without the timestamp features ['Year','Quarter'].

**Second Mean-Point Time Series Modeling:**

The pipeline of this approach is built to take an instance X, and produce a time series output from the full dataset that best represent X with the **Mean Point Scheme Function**. The time series data is then forecasted using baseline models **ARIMAX & SARIMAX** and the **LSTM model**.


## Datasets Reference

- for Trades data: https://www.kaggle.com/datasets/nishiodens/japan-real-estate-transaction-prices
- for Housing Consumer Price index: https://fred.stlouisfed.org/series/JPNCPGRHO01IXOBQ


```python

```
