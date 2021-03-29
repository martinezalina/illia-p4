
# AU Illia CABA
#### Time Series Forecasting



## Objetivo

El objetivo de este proyecto es predecir el tránsito vehicular de la AU Illia (CABA), a partir de los datos históricos de la misma.

## Datos

https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-unidades-peaje-ausa

https://datos.gob.ar/dataset/energia-precios-surtidor---resolucion-3142016/archivo/energia_80ac25de-a44a-4445-9215-090cf55cfda5

## EDA

- Time Series resample
- Missing Values
- Atypical Values / Outliers
- Interpolation Methods(Nearest)
- Autocorrelation
- Seasonal Components (Additive / Multiplicative)
- Residual histogram

## Modelos

- Benckmark: XGBoost Regressor + GridSearchCV
- LSTM Univariable
- LSTM Multivariable
- LSTM con autoencoders

## Métrica

- RMSE

## Tech stack

- Python
- Pandas
- Numpy
- Matplotlib
- Sklearn
- sqrt
- Plotly
- Keras