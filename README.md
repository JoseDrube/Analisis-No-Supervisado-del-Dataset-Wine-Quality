# 🍷 Descubrimiento de Patrones Ocultos en Wine Quality mediante Aprendizaje No Supervisado
📊 Descripción del Proyecto

Este proyecto tiene como objetivo explorar la estructura interna del dataset Wine Quality utilizando técnicas de Machine Learning no supervisado. A diferencia de los enfoques predictivos tradicionales, el aprendizaje no supervisado permite identificar patrones, relaciones y agrupaciones naturales dentro de los datos sin depender de etiquetas predefinidas.

A través de un workflow completo de Ciencia de Datos, se aplicaron algoritmos de clustering y técnicas avanzadas de reducción de dimensionalidad para analizar cómo se organizan los vinos en función de sus propiedades fisicoquímicas.

Este trabajo demuestra el potencial del análisis no supervisado para generar insights valiosos en datasets multidimensionales.

🎯 Objetivos

Realizar un Análisis Exploratorio de Datos (EDA) exhaustivo

Comprender la distribución y relación entre variables fisicoquímicas

Detectar patrones ocultos en el dataset

Identificar agrupaciones naturales mediante algoritmos de clustering

Evaluar la calidad de los clusters con métricas cuantitativas

Mejorar la interpretabilidad mediante técnicas de visualización

🧠 Metodología

El proyecto se desarrolló siguiendo un pipeline estructurado de Data Science:

🔹 Preparación de Datos

Eliminación de registros duplicados

Verificación de valores faltantes

Análisis de distribuciones

Detección de outliers

🔹 Análisis Exploratorio (EDA)

Matrices de correlación

Visualización de distribuciones

Estudio de relaciones entre variables

🔹 Algoritmos de Clustering

Se implementaron distintos enfoques para identificar estructuras en los datos:

K-Means → Modelo principal de segmentación

DBSCAN → Método basado en densidad para comparar resultados

🔹 Reducción de Dimensionalidad

Para facilitar la interpretación de datos de alta dimensión se utilizaron:

PCA (Principal Component Analysis)

t-SNE

UMAP

Estas técnicas permitieron visualizar patrones complejos en espacios bidimensionales.

🚀 Principales Hallazgos

✅ K-Means resultó ser el algoritmo más efectivo, logrando una separación clara en dos clusters que se corresponden en gran medida con los vinos tintos y blancos.

✅ Las variables fisicoquímicas contienen suficiente información para diferenciar naturalmente ambos tipos de vino sin necesidad de etiquetas.

⚠️ No se observó una segmentación significativa en relación con la calidad del vino, lo que sugiere que esta variable podría depender de relaciones más complejas o no lineales.

✅ UMAP se destacó como la técnica más eficiente, ofreciendo un excelente equilibrio entre velocidad de procesamiento y preservación de la estructura de los datos.

📈 Conclusión

Este proyecto evidencia el valor del aprendizaje no supervisado para revelar estructuras ocultas dentro de datasets complejos.

La combinación de algoritmos de clustering con técnicas modernas de visualización permitió mejorar la interpretabilidad de los datos y obtener una comprensión más profunda de su organización interna.

Como líneas futuras de trabajo, se propone:

Profundizar el feature engineering

Explorar nuevos hiperparámetros

Evaluar algoritmos adicionales de clustering

Incorporar nuevas variables

Combinar enfoques supervisados y no supervisados

🛠️ Tecnologías Utilizadas

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

👨‍🔬 Autor

Jose F. Drube
Biólogo | Data Science | Machine Learning

UMAP

t-SNE
