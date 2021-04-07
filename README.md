# apple-stock-price-prediction

download all the required libraries on your pc 
for running the keras in your enviroment we have to install tenserflow version should be more then 2.1

we have used LSTM model to predict the stock price of apple 

In last you can see we use the model to predict the stock price of 2020-12-18 and we find the actual diffrence of our predicted moel was of $4

import math,
import pandas_datareader as web,
import numpy as np,
import pandas as pd,
from sklearn.preprocessing import MinMaxScaler,
from keras.models import Sequential,
from keras.layers import Dense,LSTM,
import matplotlib.pyplot as plt
