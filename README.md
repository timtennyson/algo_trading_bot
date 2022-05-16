# Algorithmic Trading Bot

This application uses computer algorithms to buy and sell more effectively than human traders.


The steps for this project are divided into the following sections:

1. Import the Data 
2. Establish a Baseline Performance
3. Tune the Baseline Trading Algorithm
4. Evaluate a New Machine Learning Classifier

---

## Technologies

This project leverages Anaconda and JupyterLab with Python 3.9:

* [Anaconda](https://www.anaconda.com/products/individual) 

Need to import the following libraries and dependencies:

```
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

```

---

## Installation Guide

This application is a jupyter lab notebook designed to be executed using Jupyter lab.

## Import the data

The first part of the application imports historic price data and loads it into a dataframe so that it can be modeled and used to create stratgies.

## **Establish a Baseline Performance**

Baseline performance is established using a 4/100 SMA strategy and a training period of 3 months.

## Tune the baseline trading algorithm

Here we experiment with various training periods and moving average values in order to produce the optimal results. The best result observed is an 80/200 period SMA using a trading period of 5 months.

Below are examples:

!(3_month_plot)
Baseline result using 4/100 SMA and a 3 month training period

!(80_200_MA_5_MO.png)
Optimal result using 80/200 SMA and a 5 month training period

## **Evaluate a New Machine Learning Classifier**




---

## Contributors

Tim Tennyson
email: ttennyson.xyz@gmail.com
(831) 201-3845