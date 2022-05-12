# Immigration-Flow-MiniProject
Exploring immigration patterns within countries.


Dataset: OECD International Migration Database

The objective was to analyze the inflow and outflow patterns of 35 countries.
Python was used to read, clean, and store a CSV file.

# Observations:

- Germany has the top inflows and outflows: solidifying its position as a major hub in Europe.
- G7 countries have a high positive correlation with annual total inflows: R = .734, P Val = 6.88e^-8.
- G7 countries are weakly correlated when looking at EVERY nationality that immigrates per year, eg. total immigration from Afghanistan or Moldova in any year predicted by G7 status: R = .157, P Val = 0.0. 
- G7 countries have no stastically significant relationship with annual total outflow (though this is inaccurate as outflow data is missing from many countries): R = -.08, P Val = .58.
- G7 countries have no correlation when looking at EVERY nationality that emmigrates per year, eg. total emmigratin by those from Afghanistan or Moldova in any year predicted by G7 status: R = .059, P Val = 3.385e^-54.
 

# Install
pip install numpy | conda install numpy

pip install pandas | conda install pandas

pip install matplotlib | conda install matplotlib

pip install seaborn | conda install seaborn

pip install scipy | conda install -c anaconda scipy

# Import
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

%matplotlib inline

import scipy.stats as st
