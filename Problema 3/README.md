# Problema 3 - TP N°1 - AAII

## **Enunciado**
En este problema, se proporciona un conjunto de datos que contiene imágenes de escenas naturales de todo el mundo. El objetivo es construir un modelo de clasificación utilizando redes neuronales convolucionales (CNN) para clasificar estas imágenes en una de las seis categorías predefinidas.

#### Dataset
El dataset proporcionado contiene alrededor de 25,000 imágenes de tamaño 150x150, distribuidas en seis categorías:
* **buildings**
* **forest**
* **glacier**
* **mountain**
* **sea**
* **street**

Las imágenes están divididas en tres conjuntos:
* **Train**: Alrededor de 14,000 imágenes para entrenamiento.
* **Test**: Alrededor de 3,000 imágenes para evaluación del modelo.
* **Prediction**: Alrededor de 7,000 imágenes para predicción final.

#### Objetivo
Utilizando el dataset proporcionado, el objetivo es construir y comparar el rendimiento de distintos modelos de clasificación de imágenes utilizando redes neuronales convolucionales y densas que puedan clasificar con precisión las imágenes de escenas naturales en una de las seis categorías mencionadas anteriormente.

Los modelos a diseñar son:
* **Modelo con capas densas.**
* **Modelo con capas convolucionales y densas.**
* **Modelo que incluya bloques residuales identidad.**
* **Modelo que utilice como backbone alguna de las arquitecturas disponibles en TensorFlow (transfer learning)**: [https://www.tensorflow.org/api_docs/python/tf/keras applications](https://www.tensorflow.org/api_docs/python/tf/keras/applications). 

Se debe entrenar y evaluar cada modelo utilizando técnicas adecuadas de validación y métricas de evaluación de clasificación.

## **Recursos**
### 'Problema 3.ipynb'
Todo los algoritmos necesarios para resolver el problema se encuentra en este archivo.