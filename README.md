# Evaluación Parcial 1 - Fashion MNIST 🧠👕👟

Este proyecto consiste en una evaluación parcial en la que se utiliza el conjunto de datos **Fashion MNIST** para entrenar y evaluar modelos de clasificación de imágenes mediante **redes neuronales** utilizando **Python** y **TensorFlow/Keras** en un entorno **Jupyter Notebook**.

## 📌 Objetivos

- Comprender el uso de datasets de imágenes en el ámbito de Machine Learning.
- Implementar modelos de redes neuronales simples usando TensorFlow y Keras.
- Evaluar el rendimiento del modelo utilizando métricas como la precisión.
- Visualizar imágenes y predicciones de las clases del conjunto Fashion MNIST.

## 🧠 Modelo Utilizado

Se implementó una red neuronal secuencial que incluye:

- Capa de entrada (`Flatten`) para aplanar las imágenes de 28x28 píxeles.
- Capas ocultas densas (`Dense`) con funciones de activación ReLU.
- Capa de salida con activación `softmax` para clasificar en 10 categorías.

## 📚 Dataset

El dataset **Fashion MNIST** contiene 70.000 imágenes en escala de grises de artículos de ropa y accesorios, divididas en:

- 60.000 imágenes para entrenamiento.
- 10.000 imágenes para prueba.

Cada imagen tiene dimensiones de 28x28 píxeles y pertenece a una de las siguientes categorías:

0 = T-shirt/top
1 = Trouser
2 = Pullover
3 = Dress
4 = Coat
5 = Sandal
6 = Shirt
7 = Sneaker
8 = Bag
9 = Ankle boot


## ⚙️ Tecnologías Utilizadas

- Python 🐍
- Jupyter Notebook 📒
- TensorFlow / Keras 🤖
- Matplotlib 📊
- NumPy 🔢

## 🖼️ Resultados

- Visualización de datos de entrenamiento y prueba.
- Evaluación del modelo (accuracy, pérdida).
- Visualización de predicciones con imágenes y etiquetas reales/predichas.

## 🚀 Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/fegenau/DeepLearnin1
   ```

2. Abrir el archivo Evaluación_Parcial_1_Fashion_MNIST.ipynb en Jupyter Notebook o Google Colab.

3. Ejecutar todas las celdas paso a paso.
   
## 👨‍🏫 Autor

-Nombre: Francisco Egenau

-Institución: Duoc UC

-Docente: Felipe Zambrano

-Fecha: Mayo 2025

