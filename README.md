# Statistical models for forecasting
## Resources  

- Software:
    - [prophet](https://facebook.github.io/prophet/)
    - [NeuralProphet](http://neuralprophet.com/model-overview/)
    - [statsmodels](https://www.statsmodels.org/stable/index.html)
    - [xgboost](https://xgboost.readthedocs.io/en/latest/get_started.html)
- Books:
    - [Hyndman, Athanasopoulos - Forecasting: Principles and Practice](https://otexts.com/fpp2/)
- Posts:
    - [Tiwari - Let’s Forecast Your Time Series using Classical Approaches](https://towardsdatascience.com/lets-forecast-your-time-series-using-classical-approaches-f84eb982212c)
    - [Dagrada - ML time series forecasting the right way](https://towardsdatascience.com/ml-time-series-forecasting-the-right-way-cbf3678845ff)
    - [Flovik - How (not) to use Machine Learning for time series forecasting: Avoiding the pitfalls](https://towardsdatascience.com/how-not-to-use-machine-learning-for-time-series-forecasting-avoiding-the-pitfalls-19f9d7adf424)
    - [Dotis-Georgiou - Autocorrelation in Time Series Data](https://dzone.com/articles/autocorrelation-in-time-series-data)
    - [Abu -Seasonal ARIMA with Python](https://www.seanabu.com/2016/03/22/time-series-seasonal-ARIMA-model-in-python/)
- Data:
    - [Peyton Manning](https://github.com/facebook/prophet/blob/master/examples/example_wp_log_peyton_manning.csv)

## Install hints
Seems that `fbprophet` needs `pystan` and `pandas` as already installed modules.
```
pip install pystan pandas
pip install fbprophet statsmodels
```
