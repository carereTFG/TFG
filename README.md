# TFG
# Análisis clúster para el estudio longitudinal de la progresión cerebral en la enfermedad de Alzheimer

Este repositorio contiene el código para el Trabajo de Fin de Grado (TFG) en Ciencia de Datos. 
Los datos utilizados son medidas morfológicas cuantitativas (volumen, grosor cortical, área superficial, etc.) extraídas de imágenes de resonancia magnética estructural.


## 🎯 Objetivo
Analizar la influencia del alelo APOE4 y el diagnóstico basal (DX_bl) en la morfología cerebral utilizando modelos lineales mixtos, PCA y análisis de clústeres sobre datos de neuroimagen estructural.

## 📁 Estructura
- `Limpieza_Datos`: script de la limpieza de datos en Google Colab (Python).
- `Modelo_APOE4`: modelo estadístico tieniendo en cuenta el APOE4 (además de otras covariables) junto con PCA, ANOVA, biplots, ...
- `Modelo_DX_bl`: modelo estadístico tieniendo en cuenta el DX_bl (además de otras covariables) junto con PCA, ANOVA, biplots, ...
- `Cerebro_APOE4`: imagen de los resultados del PCA sobre el modelo APOE4 en el cerebro tridimensional.
- `Cerebro_DX_bl`: imagen de los resultados del PCA sobre el modelo DX_bl en el cerebro tridimensional.

## ⚠️ Nota
Los datos utilizados están anonimizados y no incluidos en el repositorio por motivos de privacidad.

## 👤 Autor
Trabajo realizado por Carla Redón, estudiante de Ciencia de Datos (curso 2024-2025).
