# 🧠 Clasificación de imágenes con Deep Learning: Fashion MNIST

Este proyecto utiliza una red neuronal profunda para clasificar prendas de vestir del conjunto de datos **Fashion MNIST**. Se desarrolló y entrenó el modelo en Google Colab utilizando TensorFlow/Keras. Además, se implementaron técnicas de regularización, análisis de hiperparámetros y visualización de resultados.

---

## 📂 Contenido del Notebook

### 1. Carga de datos
- Se importa el dataset `Fashion MNIST` desde `keras.datasets`.
- Se dividen los datos en sets de entrenamiento y prueba.

### 2. Exploración de datos
- Se visualizan algunas imágenes del dataset.
- Se identifican las clases a predecir (camiseta, pantalón, zapato, etc.).

### 3. Preprocesamiento
- Normalización de los pixeles (valores entre 0 y 1).
- División adicional en set de validación.

### 4. Creación del modelo base
- Red neuronal simple con capas densas.
- Función de activación: `ReLU` y `Softmax`.

### 5. Entrenamiento y evaluación
- Se entrena el modelo con los datos preprocesados.
- Se grafican las curvas de pérdida y precisión.
- Se evalúa el modelo en el set de prueba.

### 6. 🛡️ Regularización
- Se prueban distintas técnicas para evitar el sobreajuste:
  - **Dropout**
  - **Batch Normalization**
  - **EarlyStopping**
- Se comparan los modelos con y sin regularización.

### 7. ⚙️ Hiperparámetros
- Se ajustan y prueban:
  - `learning rate`
  - `batch size`
  - número de `epochs`
- Se identifican combinaciones óptimas.

### 8. 🔍 Análisis de predicciones
- Se visualizan imágenes mal clasificadas.
- Se identifican patrones comunes en los errores.

---

## 📊 Resultados

| Modelo                 | Precisión validación |
|------------------------|----------------------|
| Modelo Base            | 0.87                 |
| Modelo con Dropout     | 0.88                 |
| Batch Normalization    | 0.89                 |
| Dropout + BatchNorm + EarlyStopping | **0.91** |

El mejor modelo fue aquel que combinó múltiples técnicas de regularización y paró el entrenamiento en el momento óptimo.

---

## 📌 Conclusiones

- Las técnicas de regularización permiten mejorar la **generalización** del modelo, reduciendo el sobreajuste.
- Un buen ajuste de **hiperparámetros** es crucial para obtener un rendimiento competitivo.
- El análisis de errores permite entender las limitaciones del modelo y plantear mejoras futuras, como:
  - Uso de **redes convolucionales (CNN)**
  - **Data augmentation**
  - **Transfer learning**

---

## 🚀 Requisitos

- Python 3.x
- TensorFlow 2.x
- Google Colab (opcional pero recomendado)

---

## ✍️ Autor

Proyecto desarrollado como parte de una evaluación parcial del curso de Deep Learning - Ingeniería en Informática mención Ciencia de Datos.
