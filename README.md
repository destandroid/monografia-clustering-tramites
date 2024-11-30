# Análisis de Clustering en Trámites Gubernamentales
Este repositorio contiene los datos, scripts y resultados relacionados con el análisis de clustering aplicado a trámites gubernamentales. El objetivo principal es segmentar los datos utilizando algoritmos como K-Means, DBSCAN y clustering jerárquico, y generar gráficos y salidas interpretables para apoyar la toma de decisiones.

## Contenido del Repositorio

### Archivos de Datos

* tramites_gob_bo.csv: Dataset original de trámites gubernamentales, utilizado como base para los análisis.

* tramites_gob_bo_preprocesado_one_hot_weka.csv: Dataset preprocesado con codificación one-hot y ajustes adicionales para que sea compatible con Weka.

### Script de Preprocesamiento y Visualización

* Proceso.ipynb: Notebook de Jupyter que incluye los pasos de preprocesamiento realizados en el dataset, así como la generación de gráficos, como el método del codo y los heatmaps.
  
### Archivos de Resultados (Salidas de Weka)

* DBSCAN_K3: Archivo que contiene las salidas del algoritmo DBSCAN configurado con k=3, generado en Weka.

* DBSCAN_K4: Archivo que contiene las salidas del algoritmo DBSCAN configurado con k=4, generado en Weka.

* KMEANS_K3: Salidas del algoritmo K-Means con k=3, generado en Weka.

* KMEANS_K4: Salidas del algoritmo K-Means con k=4, generado en Weka.

* hiericical-complete3: Resultado del clustering jerárquico con enlace completo y configurado para tres clusters.

* hiericical-complete4: Resultado del clustering jerárquico con enlace completo y configurado para cuatro clusters.

