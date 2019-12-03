# Energy Indicators

Notebooks vontaining code, methodology and explanation for collecting data for major indicators for Canada's energy sector.

## Libraries / Requirements

Python 3.7.1

pandas 0.25.2
numpy 1.17.3
requests 2.22.0
bs4 4.8.1
zipfile
io
datetime
calendar
re 2.2.1
matplotlib 3.1.1
seaborn 0.9.0
pyxlsb
tabula-py 1.4.1

## Other
headless Chrome Browser

## About

This repository contains Jupyter Notebooks that produce major indicators (demand, production, prices, tec.)
for the energy sector in Canada. There is a Notebook for each commodity (Crude Oil, Natural Gas, Electricity).
These notebooks can be downloaded from here and run in your Python environment, or you can go to
MyBinder to run them there.

Each notebook contains the methodology for how the indicator and it's data is determined, the code to scrape and clean the data,
and visualizations of the data. Everytime the notebook is run, it will go out to the sources listed and 
collect the most recent data available at that source. All the sources used in this notebook are public and free of charge.






