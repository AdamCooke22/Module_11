# MODULE 10 CHALLENGE : Forecasting Net Profit

For this challenge we are acting as a growth analyst for MercadoLibre. We have been tasked with analyzing the company's financial and user data. We want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock. In this repository we will produce a jupyter notebook that contains our data preparation, analysis, and visualizations for all the time series data that the company needs to understand. Including visual depictions of seasonality, an evaluation of how the company's stock price correlates to its google seach traffic, and plot a forecast for the company's future revenue.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://github.com/google/pandas) - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

* [Hvplot](https://github.com/google/hvplot) - This Module provides a high-level potting API that allows for users to easily generate a wide array of plot types. HvPlot's main benefit is that it allows for very interactive visualizations.

* [Prophet](https://facebook.github.io/prophet/) - Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.



---

## Installation Guide

Before running the application first install the following dependencies.

```
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
import numpy as np

%matplotlib inline

```

---

## Usage

To use the prophet forecasting application file simply clone the repository and open the forecasting_net_prophet.ipynb file in google colab.

Upon opening the file you will have the option to run the whole note book and that will provide you with all of the calculations, evaluations, and visualizations for the analysis of the forecasting data. Some screenshots of that in action can be seen below via this link

* [SCREENSHOTS](https://github.com/AdamCooke22/module_11/tree/main/screenshots) 

## Contributors

Completed by Adam Cooke

---

## License

MIT
