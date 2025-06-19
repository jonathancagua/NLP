# 🧠 Desafíos de Procesamiento del Lenguaje Natural (PNL1)

![Estado](https://img.shields.io/badge/Estado-Completado-00b894)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Disponible-orange)
![Licencia](https://img.shields.io/badge/Licencia-MIT-blue)

Este repositorio agrupa los trabajos desarrollados como parte del curso **Procesamiento del Lenguaje Natural (PNL1)**. Cada notebook explora una técnica clave del PLN, desde enfoques estadísticos clásicos hasta modelos neuronales y sistemas conversacionales.

---

## 🔍 Desafíos Realizados

---

### 1️⃣ Clasificación de Sentimientos con Naïve Bayes

**Objetivo:**
Implementar un clasificador de sentimientos utilizando el algoritmo **Naïve Bayes** sobre reseñas de productos.
Se aplicaron técnicas de preprocesamiento, vectorización con **TF-IDF**, entrenamiento supervisado y evaluación mediante métricas como precisión, recall y F1-score.

📎 [Abrir en Colab](https://github.com/jonathancagua/NLP/blob/main/EX/Desafio_1.ipynb)

---

### 2️⃣ Vectores de Palabras con Word2Vec

**Objetivo:**
Entrenar un modelo de **Word2Vec** con la librería Gensim sobre el texto de *Don Quijote de la Mancha*.
El corpus fue tokenizado y normalizado usando **spaCy**. Se exploraron relaciones semánticas mediante visualización de embeddings en 2D/3D (PCA, t-SNE), y se realizaron pruebas de analogías y similitud semántica.

📎 [Abrir en Colab](https://github.com/jonathancagua/NLP/blob/main/EX/Desafio_2.ipynb)

---

### 3️⃣ Modelo de Lenguaje con RNN carácter a carácter

**Objetivo:**
Construir un modelo de lenguaje carácter a carácter usando redes neuronales recurrentes (**LSTM**, **GRU**).
El modelo fue entrenado para predecir la siguiente letra en una secuencia, permitiendo luego generar texto de manera automática. Se evaluó su rendimiento con perplejidad y se probaron diferentes estrategias de muestreo como greedy, beam search y temperatura.

📎 [Abrir en Colab](https://github.com/jonathancagua/NLP/blob/main/EX/Desafio_3.ipynb)

---

### 4️⃣ Bot Conversacional con datos de ConvAI2

**Objetivo:**
Crear un bot conversacional utilizando datos del dataset **ConvAI2**.
Se trabajó con datos reales de diálogos en inglés para entrenar un modelo que responda de forma coherente y relevante a entradas del usuario. Este prototipo sienta las bases para desarrollar sistemas conversacionales más complejos.

📎 [Abrir en Colab](https://github.com/jonathancagua/NLP/blob/main/EX/Desafio_4.ipynb)

---

## 📝 Notas

* Todos los notebooks están diseñados para funcionar directamente en **Google Colab**.
* Se recomienda activar el uso de **GPU** para acelerar el entrenamiento de modelos.
* Cada desafío está documentado con explicaciones detalladas para facilitar su comprensión.

---

## 👨‍💻 Autor

**Nombre:** Jonathan Cagua
**Email:** [jonathan.cagua@gmail.com](mailto:jonathan.cagua@gmail.com)
**Curso:** Procesamiento del Lenguaje Natural (PNL1) – 2025
**Institución:** \[FIUBA]

---
