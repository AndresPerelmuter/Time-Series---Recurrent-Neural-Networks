# Time-Series---Recurrent-Neural-Networks

**Descripción General**
Este proyecto realiza un análisis de ventas utilizando técnicas de deep learning, con un enfoque en la predicción de ventas. Se emplea una Red Neuronal Recurrente (RNN) para predecir las ventas futuras basándose en patrones temporales de datos históricos de ventas.

**Características Principales:**

- **Análisis Exploratorio de Datos (EDA):**
Análisis de las ventas segmentadas por edad, canal de venta, ventas online vs. ventas en tienda, ventas con descuento vs. ventas sin descuento, grupos de productos, entre otros.
- **Modelo Predictivo (RNN):**
Se entrena una RNN para predecir las ventas futuras utilizando patrones temporales en los datos históricos de ventas.
- **Evaluación del Modelo:**
El modelo se evalúa utilizando métricas comunes de error:
RMSE: 82.65
MAPE: 8.84%

Pasos:
- Preprocesamiento de Datos: Los datos son limpiados y procesados, incluyendo el manejo de valores nulos y la codificación de variables categóricas.
- Entrenamiento del Modelo: La RNN es entrenada con un conjunto de características, incluyendo datos históricos de ventas, y probada con datos no vistos.
- Evaluación de Resultados: El rendimiento del modelo se evalúa utilizando métricas como RMSE y MAPE.
- Visualización: Los datos de ventas reales y predichas se visualizan para evaluar el rendimiento del modelo.
