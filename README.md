# Práctica 2 – Spotify Data Analysis and Prediction

## Español

Este repositorio contiene la práctica 2 de análisis y modelado en R para predecir la popularidad de canciones usando un dataset de Spotify. Incluye:

1. **Descripción del conjunto de datos**  
   Variables categóricas (`spotify_id`, `name`, `artists`, `country`, `is_explicit`, `album_name`, `key`, `mode`, `time_signature`) y numéricas (`daily_rank`, `daily_movement`, `weekly_movement`, `snapshot_date`, `duration_ms`, `danceability`, `energy`, `loudness`, `speechiness`, `acousticness`, `liveness`, `instrumentalness`, `valence`, `tempo`, `popularity`, `album_release_date`) :contentReference[oaicite:7]{index=7}.

2. **Preparación y limpieza de datos**  
   Lectura del CSV, tratamiento de valores nulos y escalado de variables.

3. **Análisis exploratorio**  
   Estadísticas descriptivas y visualización de distribuciones y correlaciones con `ggplot2`, `gridExtra` y `reshape2` :contentReference[oaicite:8]{index=8}.

4. **Modelado con Random Forest**  
   Entrenamiento de un modelo Random Forest para clasificación/regresión: muestreo bootstrap, construcción de árboles y votación/promedio de predicciones.

5. **Clustering con k-means**  
   Agrupación de canciones en clusters mediante k-means: inicialización de centroides, asignación, actualización e iteración hasta convergencia :contentReference[oaicite:9]{index=9}.

6. **Ajuste de hiperparámetros**  
   Estrategias para generar grids de hiperparámetros y validación cruzada.

7. **Resultados y evaluación**  
   Métricas de rendimiento de los modelos y visualización de resultados.

Cada apartado incluye código comentado, opciones por línea de comandos y ejemplos de gráficos.

---

## English

This repository contains Practical 2 of data analysis and modeling in R to predict song popularity using a Spotify dataset. It covers:

1. **Dataset Description**  
   Categorical variables (`spotify_id`, `name`, `artists`, `country`, `is_explicit`, `album_name`, `key`, `mode`, `time_signature`) and numerical variables (`daily_rank`, `daily_movement`, `weekly_movement`, `snapshot_date`, `duration_ms`, `danceability`, `energy`, `loudness`, `speechiness`, `acousticness`, `liveness`, `instrumentalness`, `valence`, `tempo`, `popularity`, `album_release_date`) :contentReference[oaicite:10]{index=10}.

2. **Data Preparation & Cleaning**  
   Reading the CSV, null handling, and feature scaling.

3. **Exploratory Analysis**  
   Descriptive statistics and visualization using `ggplot2`, `gridExtra`, and `reshape2` :contentReference[oaicite:11]{index=11}.

4. **Random Forest Modeling**  
   Training a Random Forest model for classification/regression: bootstrap sampling, tree construction, and voting/averaging predictions.

5. **k-means Clustering**  
   Grouping songs into clusters with k-means: initialization, assignment, centroid update, and iteration to convergence :contentReference[oaicite:12]{index=12}.

6. **Hyperparameter Tuning**  
   Strategies for grid generation and cross-validation.

7. **Results & Evaluation**  
   Model performance metrics and result visualization.

Every section includes fully commented code, command-line options, and example plots.
