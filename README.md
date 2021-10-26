# Unit-10-Time-Series-Regression
Time-Series and Linear Regression Forecasting

## Time-Series Forecasting

Decomposition using a Hodrick-Prescott Filter.

Forecasted returns using an ARMA Model.

Forecasted the Settle Price using an ARIMA Model.

Forecasted volatility with GARCH.

## Linear Regression Forecasting

Built a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

## Model Conclusions

In review of the ARMA and ARIMA models - the future returns and 5 day price forecast suggests a positive increase, so one should buy the yen.

Risk of the yen is expected to increase based on the Final Forecast plot.

The ARMA and GARCH models have lower AIC and BIC values than the ARIMA model, so one should rely more on those two models given the lower values are generally better to estimate the quality of the models.

The model performed better on the out-of-sample data (testing data) vs. the in-sample data (training data), with a lower root mean squared error (RMSE) in the former.