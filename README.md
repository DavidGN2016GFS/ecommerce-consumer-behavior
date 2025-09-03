Índice Modelo Personalizado para Proyecto de Análisis de Comportamiento del Consumidor

1. Introducción

1.1. Planteamiento del problema: comprender patrones de compra y segmentar consumidores.

1.2. Objetivos del proyecto:

Identificar variables que más influyen en la satisfacción y lealtad del cliente.

Evaluar qué factores predicen la probabilidad de compra impulsiva vs planificada.

Probar modelos de machine learning para clasificar y predecir comportamientos.

1.3. Alcance y limitaciones: dataset ficticio / simulado, no representa una población real.

1.4. Herramientas utilizadas: Python, pandas, matplotlib, seaborn, scikit-learn, Keras.

2. Fortalezas del Trabajo

2.1. Exploración exhaustiva del dataset (estadísticas, nulos, correlaciones).

2.2. Enfoque en variables relevantes para segmentación de clientes.

2.3. Implementación de modelos clásicos y una red neuronal para predicción.

3. Exploración de los Datos

3.1. Descripción del dataset (columnas: demográficas, de compra, fidelización, etc.).

3.2. Revisión de atributos con shape, info() y describe().

3.3. Análisis de valores nulos y outliers en columnas como Purchase_Amount y Age.

3.4. Correlaciones entre variables (ej. entre Discount_Sensitivity y Discount_Used).

3.5. Visualizaciones:

Pie charts (género, marital status, income level).

Countplots (categorías de producto, métodos de pago, canales de compra).

Boxplots (gasto según nivel de ingreso, satisfacción según frecuencia de compra).

Heatmaps (correlaciones entre variables numéricas: satisfacción, lealtad, rating).

4. Preprocesamiento y Feature Engineering

4.1. Eliminación de columnas irrelevantes (ej. Customer_ID).

4.2. Transformación de categóricas con get_dummies (ej. Payment_Method, Gender).

4.3. Escalado de datos numéricos (Purchase_Amount, Time_to_Decision, Age).

4.4. Selección de variables significativas (chi-cuadrado aplicado a categóricas).

4.5. Comparación del dataset antes y después del preprocesamiento.

5. Implementación de Modelos

5.1. SVM (Support Vector Machine)

Kernel RBF, ajuste de hiperparámetros (C=5).

Métricas de recall vs precisión para predicción de Purchase_Intent.

5.2. Random Forest

Optimización con GridSearchCV.

Importancia de variables (ej. Brand_Loyalty, Discount_Used, Purchase_Channel).

5.3. Red Neuronal Artificial (ANN)

Arquitectura secuencial con 3 capas ocultas.

Entrenamiento de 100 épocas, batch size definido, optimizador Adam.

Evaluación del desempeño en clasificación de satisfacción del cliente.

6. (Opcional) Tareas NLP

6.1. Vectorización con TF-IDF.

6.2. Análisis de sentimiento sobre Customer Reviews.

6.3. Visualizaciones de soporte (wordclouds, distribuciones de polaridad).

7. Resultados y Comparación de Modelos

7.1. Métricas de desempeño (accuracy, precision, recall, F1-score, AUC).

7.2. Comparativa entre SVM, Random Forest y ANN.

7.3. Interpretación de las variables más influyentes en la predicción.

8. Conclusiones y Trabajo Futuro

8.1. Hallazgos principales: factores clave en la decisión de compra.

8.2. Fortalezas y limitaciones de los modelos implementados.

8.3. Posibles mejoras: modelos de boosting (XGBoost, LightGBM), más datos longitudinales.

8.4. Relevancia de los resultados para marketing y segmentación de clientes.

9. Referencias

9.1. Bibliografía académica sobre comportamiento del consumidor.

9.2. Documentación oficial de scikit-learn y Keras.

10. Anexos

10.1. Código fuente del análisis.

10.2. Gráficos complementarios.

10.3. Tablas de resultados adicionales.
