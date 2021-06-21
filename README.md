# Utilización de técnicas basadas en *random forest* y redes neuronales para mantenimiento predictivo

En este repositorio se aloja el código de mi TFM del Máster en Tratamiento Estadístico-Computacional de la Información (TECI) de la UCM-UPM.

Se desarrolla este trabajo a partir del IDA 2016 Industrial Challenge: *APS Failure prediction for Scania Trucks*.

En este trabajo se describen las tareas seguidas para solucionar un problema de mantenimiento predictivo que consiste en utilizar técnicas de aprendizaje automático para predecir si un componente específico del sistema de aire comprimido de un camión pesado se enfrentará a un fallo inminente. Este problema se modela como un problema de clasificación, ya que el objetivo es determinar si una instancia no observada representa un fallo o no. Se evaluan varios algoritmos de clasificación y se investiga cómo tratar con un conjunto de datos desbalanceado y con gran cantidad de valores ausentes. El enfoque se compone de cuatro pasos: (i) la creación de tres conjuntos de datos distintos aplicando diversas técnicas de tratamiento de datos; (ii) la creación de varios modelos de aprendizaje automático; (iii) el ajuste de sus hiperparámetros y del umbral de probabilidad para las predicciones, y (iv) la comparación de resultados entre los distintos modelos sobre los conjuntos creados para determinar la mejor solución. Los resultados muestran que una buena imputación de los valores ausentes y el ajuste del umbral de probabilidad son factores clave a la hora de mejorar el rendimiento de los clasificadores.

El código está dividido en tres *Notebooks*:

- En el primero (`TFM-JRA_01_EDA.ipynb`) se puede encontrar la parte de la descripción del conjunto de datos.

- El segundo (`TFM-JRA_02_RF.ipynb`) contiene los modelos de random forest implementados.

- Y el último (`TFM-JRA_03_NN.ipynb`) incluye los modelos de redes neuronales y la comparación de los resultados.
