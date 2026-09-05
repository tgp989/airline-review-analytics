# Proyecto Final – Airline Review Analytics

## Descripción del proyecto

Este proyecto desarrolla un análisis de reseñas de clientes de aerolíneas con el propósito de identificar patrones en las experiencias reportadas por los pasajeros y caracterizar diferentes grupos de opiniones.

El análisis combina técnicas de aprendizaje no supervisado y procesamiento de lenguaje natural para explorar las características de las reseñas y relacionarlas con la percepción de satisfacción de los clientes.

A partir de la información disponible se aplican diferentes métodos de agrupamiento y análisis de sentimiento, permitiendo abordar las reseñas desde una perspectiva tanto cuantitativa como textual.

---

## Objetivo

Analizar las reseñas de clientes de diferentes aerolíneas mediante técnicas de análisis de datos, clustering y análisis de sentimiento, con el fin de identificar patrones y características comunes en las experiencias reportadas por los pasajeros.

### Objetivos específicos

- Preparar y explorar la información contenida en las reseñas.
- Analizar las principales características de las opiniones de los clientes.
- Aplicar diferentes técnicas de agrupamiento para identificar grupos de reseñas con características similares.
- Comparar los resultados obtenidos mediante diferentes algoritmos de clustering.
- Analizar el sentimiento presente en los textos de las reseñas.
- Relacionar las características de las opiniones con la satisfacción de los clientes.
- Utilizar visualizaciones para facilitar la interpretación de los patrones encontrados.

---

## Base de datos

El proyecto utiliza una base de datos de **reseñas de clientes de aerolíneas**, que contiene información relacionada con las experiencias y opiniones expresadas por los pasajeros.

La información permite combinar variables estructuradas con el contenido textual de las reseñas para realizar análisis de segmentación y sentimiento.

### Información utilizada

Entre los elementos analizados se encuentran:

- Información relacionada con la aerolínea.
- Características de la experiencia del pasajero.
- Valoraciones realizadas por los clientes.
- Nivel de satisfacción.
- Texto de las reseñas.

La base utilizada en el proyecto corresponde al archivo `BA_AirlineReviews.csv`.

---

## Metodología

El desarrollo del proyecto se realizó mediante las siguientes etapas:

### 1. Exploración y preparación de los datos

Se realizó una exploración inicial de la base de datos para conocer su estructura, variables disponibles y características generales.

Posteriormente, se preparó la información para las diferentes técnicas de análisis utilizadas en el proyecto.

### 2. Análisis exploratorio

Se analizaron las variables disponibles y su comportamiento mediante diferentes técnicas de exploración y visualización.

Esta etapa permitió establecer una primera aproximación a las características de las experiencias reportadas por los pasajeros.

### 3. Agrupamiento mediante K-Means

Se aplicó el algoritmo **K-Means** para identificar grupos de observaciones con características similares.

El agrupamiento permitió realizar una segmentación de los registros a partir de las variables seleccionadas para el análisis.

### 4. Agrupamiento mediante DBSCAN

Se utilizó **DBSCAN** como una segunda técnica de aprendizaje no supervisado.

Este algoritmo permitió complementar el análisis de agrupamiento y explorar la existencia de grupos y observaciones que presentan comportamientos diferenciados.

### 5. Agrupamiento jerárquico

También se aplicó un método de **clustering jerárquico aglomerativo**, con el propósito de comparar otra metodología de segmentación frente a los resultados obtenidos mediante K-Means y DBSCAN.

### 6. Análisis de sentimiento

Se incorporó **TextBlob** para realizar un análisis de sentimiento sobre el contenido textual de las reseñas.

El análisis permitió obtener medidas asociadas a la orientación de las opiniones expresadas por los pasajeros.

### 7. Interpretación y visualización

Finalmente, se utilizaron diferentes visualizaciones para comparar los grupos identificados y facilitar la interpretación de las características de las reseñas y de la percepción de los clientes.

---

## Técnicas utilizadas

- **K-Means**
- **DBSCAN**
- **Clustering jerárquico aglomerativo**
- **Análisis de sentimiento**
- **TextBlob**

---

## Herramientas utilizadas

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **TextBlob**

---

## Estructura del repositorio

```text
airline-review-analytics/
│
├── README.md
├── Proyecto_final_Santiago_Giraldo.ipynb
│
└── data/
    └── BA_AirlineReviews.csv
