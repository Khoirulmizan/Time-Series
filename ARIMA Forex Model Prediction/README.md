# ARIMA Forex Model Prediction

This folder contains an analysis of Forex exchange rates using an ARIMA (AutoRegressive Integrated Moving Average) model. The project demonstrates data preprocessing, exploratory data analysis, stationarity testing, model building, and forecasting for Forex data.

## Contents

- [Overview](#overview)
- [Files](#files)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)

## Overview

This project uses R to analyze and predict Forex exchange rates. It covers the following steps:

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Stationarity testing using Augmented Dickey-Fuller (ADF) Test
4. Data differencing (if necessary)
5. ACF and PACF plot analysis
6. ARIMA model fitting
7. Model diagnostics
8. Forecasting

## Files

- `ARIMA_Forex_Model_Prediction.md`: A Markdown file written in R containing the full analysis and model building process.
- `forex_data.csv`: Dataset containing historical Forex exchange rates.

## Requirements

To run this analysis, you need:

- R (version 3.5.0 or higher recommended)
- RStudio (for easier R Markdown execution)

Required R packages:
- forecast
- tseries
- ggplot2
- dplyr
- readr
- tidyr
- zoo

You can install these packages using the following R command:

```R
install.packages(c("forecast", "tseries", "ggplot2", "dplyr", "readr", "tidyr", "zoo"))
```

## Usage

1. Ensure you have R and RStudio installed on your system.
2. Open the `ARIMA_Forex_Model_Prediction.Rmd` file in RStudio.
3. Make sure the `forex_data.csv` file is in the same directory as the .Rmd file.
4. Run the R Markdown document to execute the analysis, view visualizations, and see results.

## Results

The analysis provides:

- Visualizations of Forex exchange rates over time
- Stationarity test results
- ACF and PACF plots for model order determination
- ARIMA model summary
- Model diagnostic plots
- Forecasts for future Forex exchange rates

For detailed results and interpretations, please refer to the `ARIMA_Forex_Model_Prediction.Rmd` file.

---

For any questions or issues, please contact the repository owner or open an issue in the main repository.