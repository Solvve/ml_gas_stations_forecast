# Fuel price prediction

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/ml_gas_stations_forecast/blob/master/LICENSE.txt)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![scikit-learn 0.23.2](https://img.shields.io/badge/scikit_learn-0.23.2-blue)](https://scikit-learn.org/stable/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description
Stores

Anonymized information about the 45 stores, indicating the type and size of store Features

Contains additional data related to the store, department, and regional activity for the given dates.

Store - the store number
Date - the week
Temperature - average temperature in the region
Fuel_Price - cost of fuel in the region
MarkDown1-5 - anonymized data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
CPI - the consumer price index
Unemployment - the unemployment rate
IsHoliday - whether the week is a special holiday week

Sales

Historical sales data, which covers to 2010-02-05 to 2012-11-01. Within this tab you will find the following fields:

Store - the store number
Dept - the department number
Date - the week
Weekly_Sales -  sales for the given department in the given store
IsHoliday - whether the week is a special holiday week

## Tasks:

    predict Fuel_Price for 1 month using all stores
    predict Fuel_Price for 1 month using all data for new (unknown) store

