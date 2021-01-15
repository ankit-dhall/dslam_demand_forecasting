# DSLAM Demand Forecasting
### Using Time-Series Analysis (ARIMA) to Forecast Market Demand and Failure Rates

This repository houses the source code and results of developing a time-series forecasting model to understand future demand and equipment failure rates.


## Table of Contents

- [Project Overview](#projectoverview)
- [Data Description](#datadescription)
- [Technical Overview](#technicaloverview)
- [Results](#results)

***

<a id='projectoverview'></a>
## Project Overview

This project aims to implement a time-series forecasting model, aimed at understanding future market demand and DSLAM usage including equipment failure rates. 

A DSLAM (Digital Subscriber Line Access Multiplexer) is used to connect users across various georgraphical areas to a high-speed digital communications channel.

Each exchange area consists of multiple DSLAMs and can have different usage rates, demand rates, and failure rates.

This analysis would help the business by understanding the growth trend, DSLAM failure rate, and future demand. This information can then be leveraged to reduce overhead costs by setting up the right DSLAm capacity for a region and conducting the required maintenance to increase total capacity.

<a id='datadescription'></a>
## Data Description

The dataset used is a weekly log consisting of the available DSLAM ports, used ports and faulty ports.
This data spans across a large number of functioning DSLAMS across various Exchanges in the UK.

The link to the dataset can be found here. [DSLAM Historical Data.txt](https://github.com/ankit-dhall/dslam_demand_forecasting/blob/main/dataset/DSLAM%20Historical%20Data.txt)

<a id='technicaloverview'></a>
## Technical Overview

The project works on building a relevant time-series forecasting model by implementing a number of time-series forecasting concepts including:

* Testing Stationarity (Augmented Dickey Fuller Test)
* Decomposing Trend, Seasonality, and Residuals
* Analyzing ACF and PACF graphs
* Implementing ARIMA to forecast a 95% confidence interval

<a id='results'></a>
## Results

The detailed jupyter notebook consisting of all the steps performed and results obtained can be referred to here. [capacity_forecasting_ARIMA.ipynb](https://github.com/ankit-dhall/dslam_demand_forecasting/blob/main/capacity_forecasting_ARIMA.ipynb)