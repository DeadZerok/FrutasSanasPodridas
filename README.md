# Clasificación de Frutas Frescas vs. Podridas con Deep Learning
---

## 💡 Descripción del Proyecto


Este proyecto se centra en el desarrollo de un sistema de **clasificación de imágenes** basado en **Deep Learning** para determinar si una fruta está **fresca o podrida**. Utiliza una **Red Neuronal Convolucional (CNN)**, específicamente una arquitectura pre-entrenada **MobileNetV2** con ajuste fino (*fine tuning*), para lograr una alta precisión en la detección.

El modelo se entrena con un **dataset balanceado de imágenes de frutas**, las cuales son preprocesadas y aumentadas para mejorar la robustez y generalización del modelo. El objetivo final es proporcionar una herramienta automatizada capaz de inspeccionar visualmente frutas, lo que tiene aplicaciones directas en la cadena de suministro alimentaria, desde la producción hasta el punto de venta.

---

## ✨ Características Principales

* **Clasificación Binaria:** Distingue eficientemente entre frutas "frescas" y "podridas".
* **Modelo Pre-entrenado (MobileNetV2):** Aprovecha el poder de una CNN optimizada para tareas de visión por computadora, permitiendo un entrenamiento más rápido y resultados precisos.
* **Aumentación de Datos:** Utiliza `ImageDataGenerator` para expandir el dataset y mejorar la capacidad de generalización del modelo.
* **Preprocesamiento de Imágenes:** Redimensiona y prepara las imágenes para la entrada al modelo, asegurando consistencia.
* **Evaluación Exhaustiva:** Incluye métricas de precisión, curvas de pérdida y exactitud, y una matriz de confusión para un análisis completo del rendimiento.
* **Visualización de Resultados:** Genera gráficos para entender el proceso de entrenamiento y el rendimiento final del modelo.

---

## Pasos del proyecto
1. Descarga y análisis del dataset: [Fruits fresh and rotten](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification)
2. Importación de librerías
3. Redimensionamiento y normalización de imágenes
4. Balanceo de clases
5. Carga y visualización de datos
6. Aplicación de MobileNetV2 on ajuste fino (*fine tuning*)
7. Entrenamiento y evaluación del modelo

---

## ⚙️ Tecnologías y Librerías Usadas

* **Python:** Lenguaje de programación principal.
* **TensorFlow / Keras:** Frameworks de Deep Learning para la construcción y entrenamiento de modelos.
* **NumPy:** Para operaciones numéricas eficientes.
* **Matplotlib:** Para la visualización de datos y gráficos.
* **Seaborn:** Para la visualización mejorada de la matriz de confusión.
* **OpenCV (cv2):** Posiblemente para preprocesamiento de imágenes (aunque `ImageDataGenerator` de Keras suele manejar gran parte).
* **Jupyter Notebook:** Entorno interactivo para el desarrollo y la exploración del código.
* **MobileNetV2
- **Jupyter Notebook

## 🧠 Aplicaciones Potenciales

Las aplicaciones de este proyecto son diversas y valiosas en varios sectores:

* **Sistemas de Clasificación en Supermercados:** Automatizar la inspección de productos perecederos para garantizar la calidad.
* **Procesos Post-cosecha en Agricultura:** Integración en líneas de producción para clasificar frutas antes de su distribución.
* **Inspección Visual Automatizada:** Reducir la necesidad de intervención manual y mejorar la eficiencia en el control de calidad.
* **Reducción de Desperdicio Alimentario:** Identificar y separar rápidamente las frutas podridas para minimizar pérdidas.

---

