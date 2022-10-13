# Proyecto Deep Learning: Precios Real Estate Madrid
#### The Bridge - Bootcamp Data Science Full-Time abril 2022

## Descripción del proyecto:

A través de este proyecto se pretende crear un modelo de deep learning capaz de predecir el valor de bienes inmuebles situados en la ciudad de Madrid, distinguiendo entre variables como el distrito y el barrio en el que están situados, el tipo de inmuebles (pisos, chalets o casas, áticos y duplex) a la vez que una gran variedad de características propias de la estructura del inmueble.

1. Se han extraido los datos de kaggle, mediante el dataset houses_Madrid.csv.
2. Se ha realizado la limpieza de columnas irrelevantes tras una observación del dataset.
3. Se ha realizado una segunda limpieza y tratado de variables tras la separación train/test, aplicando el mismo tratado en test que previamente se había utilizado para train.
4. Se han analizado los datos y tratado los outliers mediante límites de cuartiles (3er cuartil x 1.5).
5. Se ha feature encoding a las variables requeridas (dummies y hashing). 
6. Se han estandarizado las variables y preparado adecuadamente para la posterior aplicación del modelo sobre ellas.
7. Se ha entrenado el modelo de deep learning con keras y se ha visualizado su aplicación.
8. Finalmente se han observado las predicciones y obtenidas mediante el modelo y aplicado las métricas adecuadas (MAPE) para su correcta medición.

## Librerias y recursos:
Sklearn (feature_extraction, model_selection), TensorFlow (keras), Spicy, Matplotlip (pyplot), pandas y numpy.

## Archivos adjuntos:
* houses_Madrid.csv.
---
## Observaciones:

Se ha obtenido una predicción con un Mean Absolut Percentage Error de aproximadamente un 14%, aún así, tras la visualización de los resultados se puede observar como podríamos investigar cierto tratado de variables que están dando lugar a ciertos outliers en nuestra predicción, de manera que se obtuviese una menor covarianza entre el target y la predicción.

### Autor:
Antoni Suau Maget - <tonisuau30@gmail.com>

