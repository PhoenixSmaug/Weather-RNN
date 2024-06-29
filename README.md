# Weather prediction using RNNs

State-of-the-art weather models use dozens of measurement parameters that allow an accurate forecast for several days in the future. For this project, the models are restricted to only use temperature data and then solve the time series prediction model to predict the temperature six hours in advance.

As a data set, the project will use hourly temperature measurements in the German city of Mannheim from 01.01.1948 to 31.12.2023, provided by the German Weather Service DWD [here](https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/hourly/). The following models are compared with each other:
* Linear Regression
* k-Nearest Neighbours
* RNN with GRU layers
* RNN with LSTM layers

The main findings are that recurrent neural networks outperform traditional regression models on this task. And this improvement can be achieved even with very small networks that have less than 10,000 parameters.

(c) Mia Müßig
