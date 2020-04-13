# LightGBM
Uso del algoritmo LightGBM de Machine Learning

Se muestra en este proyecto el uso del algoritmo LightGBM para un problema de clasificación y para un problema de regresión

### LightGBM - Clasificación - Predict customer churn in banks

Partimos del dataset **Churn_Modelling.csv** que contiene datos de clientes bancarios recogidos durante 6 meses. La última columna del dataset "Exited" es nuestra columna objetivo y sus valores son:
- 1: indica que el cliente dejó el banco
- 0: indica que el cliente permanece en el banco

Objetivo: Modelo de machine learning que sea capaz de predecir si un cliente va a dejar el banco o no. Vamos a utilizar para ello el modelo LightGBM

Código: lightgradientboosting.ipynb

### LightGBM - Regresión - Predicción de precios Airbnb

Partimos de los ficheros csv ya limpios generados en el proyecto final del bootcamp. Este algoritmo LightGBM no se probó en la parte de Machine Learning así que lo vamos a probar aquí. Se parte de los ficheros **listings_train.csv** y **listings_test.csv**
Por temas de potencia de cálculo en este caso he utilizado Google Colaboratory

