# Análisis de Canciones en Spotify (1958-2019) con Apache Spark

Este proyecto contiene un análisis de un dataset de canciones de Spotify que abarca el período entre 1958 y 2019. El análisis se realiza utilizando Apache Spark para manejar y procesar grandes volúmenes de datos. 

## Descripción del Dataset

El dataset utilizado (`spotify_dataset.csv`) contiene 277,965 filas y 30 columnas, que cubren 24,000 canciones diferentes. Cada registro en el dataset describe el rendimiento semanal de una canción en el ranking de Spotify, con atributos como:

- **WeekID**: Identificador de la semana de registro.
- **Week Position**: Posición de la canción en esa semana.
- **Song**: Título de la canción.
- **Performer**: Nombre del intérprete.
- **SongID**: Identificador único de la canción.
- **Peak Position**: Mejor posición alcanzada por la canción.
- **Weeks on Chart**: Número de semanas en el top 100.
- **top10_tag**: Indicador si la canción estuvo en el top 10.
- **spotify_genre**: Género personalizado de Spotify.

## Tareas y Ejercicios

El notebook contiene varios ejercicios que guían al usuario a través de la manipulación de datos usando Spark. A continuación, se detallan algunos de los ejercicios incluidos:

1. **Lectura de Datos**: Lectura del dataset asegurando que Spark infiera correctamente los tipos de datos y que las filas mal formateadas sean descartadas.
  
2. **Análisis Descriptivo**: Cálculo de estadísticas básicas como la media, mediana, moda, etc., sobre las distintas columnas del dataset.

3. **Filtrado y Transformación de Datos**: Aplicación de filtros, agregaciones y otras transformaciones para obtener insights significativos del dataset.

4. **Visualización**: Creación de gráficos y visualizaciones que muestren las tendencias y patrones en los datos, como la popularidad de géneros musicales a lo largo del tiempo.

## Requisitos

Para ejecutar este notebook, necesitas tener instalado lo siguiente:

- Python 3.x
- Apache Spark
- Jupyter Notebook

También se recomienda tener experiencia básica con Apache Spark y el ecosistema de Big Data.

## Instrucciones de Uso

1. **Clona este repositorio**: 
   ```bash
   git clone https://github.com/roberolv/PySaprk_Spotify.git
   
## Instrucciones de Uso

1. **Instala las dependencias**: Asegúrate de tener Apache Spark instalado y configurado en tu entorno.

2. **Ejecuta el notebook**:

   ```bash
   jupyter notebook Spark_m2.ipynb

