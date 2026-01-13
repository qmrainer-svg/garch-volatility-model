# Volatility Forecasting with GARCH Models

This repository contains a Python Jupyter Notebook that uses GARCH family models (GARCH, EGARCH, GJR-GARCH) to forecast volatility in financial time series. ETH/USD daily data is used as an example.

## What's Inside?

* Implementation of different GARCH models (GARCH, EGARCH, GJR-GARCH) in Python (using the `arch` library).
* Testing different error distributions in the models (Normal, Student's t, Skewed Student's t).
* Using **Walk-Forward Validation** to realistically measure model performance.
* Visualization of the results (plots).
* Comparison of the models against a simple "naive" forecast (using metrics like R², RMSE).

## Files

* `Volatility_Forecasting_GARCH_ETH.ipynb`: The main Jupyter Notebook containing all the analysis and code.
* `ETH_LAST5YEAR_1D.csv`: The sample ETH/USD daily price data used in the analysis.
* *(You can also add the generated plot `.png` files here, e.g., `gjr_garch_skewt_dist_1d_walkforward_analysis_ETH.png`)*

## How to Run

1.  Clone this repository to your computer (`git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git`).
2.  Navigate into the cloned directory: `cd YOUR_REPOSITORY_NAME`.
3.  Install the required Python libraries:
    ```bash
    pip install pandas numpy matplotlib arch scikit-learn jupyterlab
    ```
4.  Launch Jupyter Lab:
    ```bash
    jupyter lab
    ```
5.  Open the `Volatility_Forecasting_GARCH_ETH.ipynb` notebook from the Jupyter interface.
6.  Follow the steps inside the notebook to execute the code cells. Make sure the data file (`ETH_LAST5YEAR_1D.csv`) is in the same directory as the notebook.

## Libraries Used

* pandas
* numpy
* matplotlib
* arch
* scikit-learn (sklearn)