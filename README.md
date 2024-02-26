# Time-Series-Forecasting

## Basic Terminologies in Time Series Forecasting
1) Stationarity
   - It refers to the data that exhibits a consistent statistical distribution over time.
2) Differencing
   - This is a technique used to make a non-stationary data stationary.
   - Involves taking the difference between consecutive observations to remove the trend or seasonality.
3) Time interval
   - The fixed amount of time between each observation in a time series. It can be same for the inputs and ouputs or a specific time interval for inputs and different time interval of ouput.
   - I have handled data where Inputs were taken between 1 hour and the ouputs were found between 15mins so that there are 4 outputs in just 1 hour.
4) Timestamp
   - The specific time at which an observation is recorded.
   - This is usually converted into sine and cosine encoding to make the model understand that this is variation of time.
5) Seasonality
   - A regular pattern of changes in a time series that occurs at fixed intervals of time.
6) Autocorrelation
   - The degree to which a time series is correlated with its own lagged values.
7) Lag
   - The amount of time between two observations in a time series.
8) Smoothing
   - The process of removing noise and other short term fluctuations from a time series to reveal its underlying trends and seasonality.
9) Trend
    - The long term pattern or direction in a time series.


References:

- [Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting](https://rezayazdanfar.medium.com/informer-beyond-efficient-transformer-for-long-sequence-time-series-forecasting-4eeabb669eb)
- [Multivariate Time Series Forecasting with Transformers](https://towardsdatascience.com/multivariate-time-series-forecasting-with-transformers-384dc6ce989b)
  - This includes the implementation of spacetimeformer.
