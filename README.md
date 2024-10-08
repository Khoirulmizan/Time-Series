# Time-Series Analysis Repository

This repository contains various time series analysis projects that focuses on data forecasting techniques.

## Table of Contents

- [Projects](#projects)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Projects

### ARIMA Forex Model Prediction

This project focuses on building an ARIMA (AutoRegressive Integrated Moving Average) model for predicting Forex exchange rates. It demonstrates data preprocessing, exploratory data analysis, stationarity testing, model building, and forecasting.

#### Files:
- `ARIMA_Forex_Model_Prediction.Rmd`: An R Markdown file containing the full analysis and model building process.
- `ARIMA-Forex-Model-Prediction.md` : A Mawrkdown file that is used to render images on github
- `ARIMA-Forex-Model-Prediction_Files/figure-gfm` : A folder containing images that are used in the Markdown file
- `forex_data.csv`: Dataset containing historical Forex exchange rates.

### To Be Decided

## Getting Started

To get started with this project, clone the repository and navigate to the project directory.

```bash
git clone https://github.com/your-username/Time-Series.git
cd Time-Series/ARIMA\ Forex\ Model\ Prediction
```

### Prerequisites

This project requires R and several R packages. Make sure you have R installed on your system. You can download R from [The Comprehensive R Archive Network (CRAN)](https://cran.r-project.org/).

Required R packages:
- forecast
- tseries
- ggplot2
- dplyr
- readr
- tidyr
- zoo

### Installation

Install the required R packages using the following commands in R:

```R
install.packages(c("forecast", "tseries", "ggplot2", "dplyr", "readr", "tidyr", "zoo"))
```

## Usage

1. Open the `.Rmd` file from the available projects in RStudio or your preferred R environment.
2. Make sure the `.csv` file is in the same directory as the .Rmd file.
3. Run the R Markdown document to see the analysis, visualizations, and results.

## Contact

Khoirul Mizan - [@seressu](https://twitter.com/seressu) - dbamizankhr@gmail.com

Project Link: [https://github.com/khoirulmizan/Time-Series](https://github.com/khoirulmizan/Time-Series)