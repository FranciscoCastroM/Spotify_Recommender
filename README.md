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

Los análisis y las visualizaciones siguieren que los géneros similares tienden ubicarse cerca al igual que las canciones por tipos; esto tiene sentido, los géneros similares suelen tener un ritmo y tempo similar.

Teniendo en cuenta lo anterior es posible construir un sistema de recomendación tomando los puntos de los datos de las canciones que el usuario está escuchando y recomendar canciones que se encuentren cercanas es decir, que correspondan a los datos cercanos. Spotipy es un cliente de Python para la API web de Spotify que facilita a los desarrolladores la obtención de datos y la consulta de canciones en el catálogo de Spotify (pip install spotipy). También es necesario crear una aplicación en la [página del desarrollador de Spotify] (https://developer.spotify.com/) y guardar su ID de cliente y clave secreta para acceder a la API.
