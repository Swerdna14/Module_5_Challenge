# Monte Carlo Financial Planning
**Module 5 Challenge**

This challenge will look at evaluating a crypto and stock portfolio to see if there will be enough value in those for an emergency fund.

Also testing to see if a credit union member can retire after 30 years or even quicker with a 10 year plan using a Monte Carlo simulation and using differently weighted stocks.

---

## Technologies

This project uses python 3.7 with the following packages:

* [Pandas](https://github.com/google/pandas) - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

* [Os](https://github.com/google/os) - This module provides a portable way of using operating system dependent functionality.

* [Requests](https://github.com/google/requests) - This Module allows you to send HTTP requests using python. The HTTP request returns a Response Object with all the response data (content, encoding, status, etc).

* [Json](https://github.com/google/json) - This module allows you to get data into a dictionary. Json is a syntax for storing and exchanging data. Json is text, written with JavaScript object notation.

* [Dotenv](https://github.com/google/dotenv) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables.

* [Alpaca_trade_api](https://github.com/google/alpaca_trade_api) - This is a python library for the Alpaca Commission Free Trading API. It allows rapid trading algo development easily, with support for both REST and streaming data interfaces. 

* [MCForecastTools](https://github.com/google/MCForecastTools) - This module allows for us to build a Monte Carlo simulation to predict the range of potential values for a portfolio.

---

## Installation Guide

In order to use this program please import and utilize the following libraries and dependencies: 

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline

```

---  

### **Run instructions:**
To run this analysis, simply clone the repository or download the files. Open a terminal instance and start a jupyter lab instance by using the following command:
```python
jupyter lab
```
Once it has opened, navigate to the file named **financial-planner.ipynb**.

---

## Contributors

This project was created as part of the module 14 challenge in the Monash University Fintech Bootcamp 2022 Program by:

Lachlan Andrews

Email: swerdna14@gmail.com

LinkedIn: lachlanjandrews
