# Advanced Time Series Forecasting with Prophet and Bayesian Optimization
This project implements a complete, production-quality forecasting workflow using Facebook Prophet, combined with Bayesian Optimization (Optuna) for hyperparameter tuning.
The goal is to improve forecasting accuracy over the standard Prophet baseline across short-term (7-day) and medium-term (30-day) horizons.

Project Highlights:
  Real-world financial dataset (S&P 500, ^GSPC)
  Data cleaning and stationarity checks
  Baseline Prophet model
  
Bayesian Optimization of:
  seasonality_prior_scale
  changepoint_prior_scale
  n_changepoints
  seasonality_mode

Forecast evaluation:
  RMSE
  MAE
  MAPE

Residual diagnostics:  
  Residual time plot
  ACF & PACF plots
  Final model selection and justification
