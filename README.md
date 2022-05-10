# Spotify_Recommender

**Objetivo** El objetivo de esta libreta es realizar un Motor de Recomendación de Canciones utilizando una base de datos pequeña de Spotify y el algoritmo K-Medias.

##Importar las librerías
1. Librerías para la manipulación de datos
2. Spotify
3. Configuración del sistema
4. Inteligencia Artificial
5. Big Data (Spark)

## Datos Utilizados:
El conjunto de datos utilizados se trata de un dataset obtenido de kaggle, el cual cuenta con un conjunto de más de 170,500 canciones, con un tamaño aproximado de 40 MB.

### Base de Datos de Spotify

https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset

## Implementación del algoritmo K-Medias (K-Means)

<img src="https://github.com/FranciscoCastroM/Spotify_Recommender/blob/main/Imagenes/kmeans.png" width="50%" height="50%">

El objetivo principal del método es agrupar las observaciones en grupos lo más semejante entre sí y que las pertenecientes a grupos distintos sean lo más desemejante entre sí. Las medias como la euclídea son utilizadas para medir la semejanza y desemejanza.

Entre sus características podemos encontrar:

- El método K-Medias divide un conjunto de  observaciones en  grupos.
- Cada grupo es representado por el promedio de los puntos que lo componen.
- El representante de cada grupo se denomina centroide.
- La cantidad de grupos , es parámetro que se debe establecer.

## Motor de recomendación.
