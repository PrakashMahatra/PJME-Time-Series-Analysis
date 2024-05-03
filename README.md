

# PJME Time Series Analysis

This repository contains code and documentation for analyzing the PJME (PJM Interconnection LLC) electricity consumption time series data using SARIMA (Seasonal Autoregressive Integrated Moving Average) and Facebook Prophet models.

## Overview

In this project, we explore the PJME electricity consumption dataset, which consists of hourly electricity consumption data from the PJM Interconnection LLC grid. The goal is to analyze the historical data, build predictive models, and forecast future electricity consumption.

## Data

The PJME hourly electricity consumption dataset contains historical electricity consumption data from the PJM Interconnection LLC grid. The data spans several years and includes hourly electricity consumption measurements.

## Models

### SARIMA Model

We use the SARIMA (Seasonal Autoregressive Integrated Moving Average) model to analyze and forecast the PJME electricity consumption time series. SARIMA is a powerful time series forecasting model that incorporates seasonality, trends, and autocorrelation.

### Facebook Prophet Model

In addition to the SARIMA model, we also explore the Facebook Prophet model for time series forecasting. Prophet is an open-source forecasting tool developed by Facebook, which is designed to handle various time series forecasting tasks with ease.

## Analysis

The analysis includes:

- Data preprocessing and exploration
- SARIMA model fitting and evaluation
- Facebook Prophet model fitting and evaluation
- Forecasting future electricity consumption
- Comparison of SARIMA and Prophet forecasts

## Results

The results of the analysis, including model performance metrics, forecasted values, and visualizations, are presented in the Jupyter Notebooks included in this repository.

## Usage

To run the analysis:

1. Clone this repository to your local machine.
2. Install the required dependencies specified in the `requirements.txt` file.
3. Open and run the Jupyter Notebooks (`sarima_analysis.ipynb` and `prophet_analysis.ipynb`) to reproduce the analysis.

## Dependencies

The following Python libraries are used in this project:

- numpy
- pandas
- matplotlib
- statsmodels
- fbprophet

Install the dependencies using the following command:

```
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize and expand this README file as needed for your specific project requirements.
