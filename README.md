# Volatility Forecasting with GARCH Models

This repository contains a Python Jupyter Notebook that uses GARCH family models (GARCH, EGARCH, GJR-GARCH) to forecast volatility in financial time series. ETH/USD daily data is used as an example.

## What's Inside?

* Implementation of different GARCH models (GARCH, EGARCH, GJR-GARCH) in Python (using the `arch` library).
* Testing different error distributions in the models (Normal, Student's t, Skewed Student's t).
* Using **Walk-Forward Validation** to realistically measure model performance.
* Visualization of the results (plots).
* Comparison of the models against a simple "naive" forecast (using metrics like R², RMSE).

## Files

* `main.ipynb`: The main Jupyter Notebook containing all the analysis and code.

## Libraries Used

* pandas
* numpy
* matplotlib
* arch
* scikit-learn (sklearn)
