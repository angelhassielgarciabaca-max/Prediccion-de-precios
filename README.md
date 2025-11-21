# Prediccion-de-precios
---
## Descripción
- Este repositorio implementa un pipeline de predicción de precios de acciones de Tesla (TSLA) utilizando dos enfoques complementarios:
- Modelos estadísticos (ARIMA) para capturar tendencias lineales y estacionalidad.
- Redes neuronales recurrentes (LSTM) para aprender patrones no lineales y dependencias de largo plazo en series temporales.
- El proyecto incluye descarga de datos históricos, exploración inicial, ingeniería de características, entrenamiento de modelos, evaluación con métricas y visualización de resultados.
 ## El flujo incluye:
- Descarga automática de datos históricos con yfinance.
- Exploración inicial y visualización de tendencias.
- Ingeniería de características (medias móviles).
- Entrenamiento de modelos ARIMA y LSTM.
- Evaluación con métricas (RMSE y MAE).
- Gráficas comparativas entre valores reales y predicciones.
### Objetivo
Comparar el desempeño de modelos estadísticos y de deep learning en la predicción de precios financieros, mostrando fortalezas y limitaciones de cada enfoque y dejando un pipeline reproducible para extender a otros activos.
