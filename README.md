# my CAS projects
This repository contains modul works for two modules done in a CAS programm - Certificate of Advanced Studies in Applied Data Science (ADS) - at the University of Bern.

## content
Both modul works (Modul2 and Modul3) found in the repository deal about electricity price forecasting for day-ahead market in switzerland. So it's about time series forecasting.
In both modules we make use of data from the transparency plattform of entsoe found on https://transparency.entsoe.eu. The Data is already prepared and provided within the repository - dataset for each modul in the modul path.

Modul2 work loads a given set of data and compares different models (i.e. linear Regressor, Random Forest Regressor) to train and fit electricity prices for switzerland by means of sklearn library.
This modul work was done in Oktober 2020.

In Modul3 extended data (i.e. enriched with time information) is given and will train and fit electricity prices for switzerland using neuronal networks models. This work makes use of a given tensorflow tutorial (see: https://www.tensorflow.org/tutorials/structured_data/time_series) and adapts different code sequences (i.e. configuration for data windowing) to approach for better results.
This modul work was done in March 2021.

These both are different approaches and for an optimal approach on the given problem of price forecasting a combination of the two methods should lead to better forcasting results (work in progress).


## Usage & Installation
Both modul works are provided in form of notebooks.
For further description refer to the readme.pdf in the repository directories of the modul:
- Modul2: navigate path to Modul2/Electricity_Price_Forecasting_20201019/README.pdf
- Modul3: navigate path to Modul3/forecasting_electricity_prices_PhWenk/README.pdf





