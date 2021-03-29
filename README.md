
# AU Illia CABA
#### Time Series Forecasting



## Objetivo

El objetivo de este proyecto es predecir el tránsito vehicular de la AU Illia (CABA), a partir de los datos históricos de la misma.

## Notebooks

El proyecto cuenta con 3 notebooks. A continuación detallamos qué contiene cada uno.

**Principal**

El notebook principal es `CABA_Series_Temporales_con_RRNN_efectivo.ipynb`. Corriendo sólo este notebook se puede evaluar todos modelos entrenados.

**Anexos**

El notebook anexo `flujo-vehicular-2020.ipynb` se creó para realizar las primeras transformaciones del dataset del flujo vehicular 2020 y hacer las primeras exploraciones del contenido. El dataset resultante se utiliza en el noteboot principal y ya está disponible en ./datasets

El notebook anexo `precios-surtidor.ipynb` se creó para trabajar el dataset de precios de combustible, y generar un dataset simplificado del precio de nafta promedio por semana en Argentina. El dataset resultante se utiliza en el noteboot principal y ya está disponible en ./datasets


## Datasets

[Flujo Vehicular por unidades de peaje AUSA](https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-unidades-peaje-ausa)

[Precios de combustible - Resolución 3142016](https://datos.gob.ar/dataset/energia-precios-surtidor---resolucion-3142016/archivo/energia_80ac25de-a44a-4445-9215-090cf55cfda5)

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