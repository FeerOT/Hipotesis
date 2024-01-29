# ProyectoHipotesis

En un mundo en el que la industria musical es extremadamente competitiva y está en permanente evolución, la capacidad de tomar decisiones basadas en datos se ha convertido en un activo invaluable.

En este contexto, una discográfica se enfrenta al emocionante desafío de lanzar un nuevo artista en el escenario musical global. Afortunadamente, cuenta con una herramienta poderosa en su arsenal: un extenso dataset de Spotify con información sobre las canciones más escuchadas en 2023.

La discográfica planteó una serie de hipótesis sobre qué hace que una canción sea más escuchada. Estas hipótesis incluyen:

- Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify.
- Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer.
- La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.
- Los artistas con un mayor número de canciones en Spotify tienen más streams totales.
- Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify.

Se debe validar (refutar o confirmar) estas hipótesis mediante el análisis de los datos, y proporcionar recomendaciones estratégicas basadas en tus hallazgos. En última instancia, el objetivo es que la discográfica y el nuevo artista puedan tomar decisiones informadas que aumenten sus posibilidades de conseguir el “éxito”.

# Base de Datos

Se cuenta con una base de datos con las siguientes caracteristicas:
- 3 tablas llamadas Track in Competition, Track in Spotify y Track Technical Info.
- Volumen de 953 lineas.
- Cuentan con 30 variables en total.

# Proceso de Limpieza y Preparación

Durante el proceso de limpieza se eliminaron las lineas con valores nulos en variables importantes como track_id.
Para los datos nulos o fuera de alcance estos fueron eliminados, sujetos al limite de no borrar mas de un 1% del total de datos.
Se dejaron las variables de texto sin caracteres especiales o numeros donde no corresponda.

# Análisis Exploratorio 

A continuación se muestra el analisis exploratorio de los datos.

![image](https://github.com/FeerOT/Hipotesis/assets/150949526/4a64d2eb-9465-417a-8606-409f6d64ef9a)

# Técnicas de Análisis Utilizadas

Durante el proceso de analisis se utilizaron las siguientes tecnicas: 
- Aplicar Segmentación
- Validación de Hipotesis
- Pruebas de Significancia 
- Regresión Lineal
- Correlación

# Resultados y Conclusiones

Los principales resultados y conclusiones obtenidos fueron:
- Se validaron o rechazaron las hipotesis planteadas por la discográfica
- Se establecieron recomendaciones para la discografica basadas en la validacion de las hipotesis

