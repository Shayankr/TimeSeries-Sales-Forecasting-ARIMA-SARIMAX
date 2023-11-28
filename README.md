# Sales Forecasting using ARIMA, SARIMA, and SARIMAX Models

![GitHub repo size](https://img.shields.io/github/repo-size/Shayankr/TimeSeries-Sales-Forecasting-ARIMA-SARIMAX)
![GitHub license](https://img.shields.io/github/license/Shayankr/TimeSeries-Sales-Forecasting-ARIMA-SARIMAX)

This repository demonstrates accurate sales forecasting using ARIMA, SARIMA, and SARIMAX models. The provided Jupyter notebook guides you through a step-by-step process to effectively predict sales trends, utilizing both temporal patterns and external factors.

## Table of Contents
- [About](#about)
- [Steps](#steps)
- [ARIMA Model](#arima-model)
- [SARIMA Model](#sarima-model)
- [SARIMAX Model](#sarimax-model)
- [Usage](#usage)
- [License](#license)

## About
In this repository, you'll find a comprehensive Jupyter notebook that showcases the power of ARIMA, SARIMA, and SARIMAX models for accurate sales forecasting. The notebook covers:
- Data visualization to understand trends
- Stationarity checks for accurate modeling
- Optimal order selection for model creation
- Correlation analysis to fine-tune predictions

## Steps
0. Importing Necessary Libraries
1. Loading and Preprocessing of Dataset (Time series data)
2. Visualize the Time Series Data
3. Check the stationarity of time series data
4. If not stationary  -- > Make the time series data stationary
5. Plot the Correlation and AutoCorrelation Charts
6. **ARIMA Model**
    - Explanation: Autoregressive Integrated Moving Average model
    - Details: Utilizes past observations and their differencing to predict future values.
7. **SARIMA Model**
    - Explanation: Seasonal Autoregressive Integrated Moving Average model
    - Details: Extends ARIMA to account for seasonality in the time series data.
8. **SARIMAX Model**
    - Explanation: Seasonal Autoregressive Integrated Moving Average model with eXogenous variables
    - Details: Incorporates external factors (exogenous variables) into the SARIMA model for enhanced forecasting.
9. Use the model to make predictions
10. Pros and Cons of ARIMA, SARIMA, and SARIMAX

## Usage
1. Clone this repository to your local machine.
2. Open the Jupyter notebook file `Sales_Forecasting_ARIMA_SARIMAX.ipynb`.
3. Follow along with the detailed steps to understand the model building process.
4. Modify and experiment with the notebook to apply these techniques to your own time series data.

Feel free to contribute improvements or share your insights!

## License
This project is licensed under the [MIT License](LICENSE).
