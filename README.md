# RNAs-NLP
Analísis de sentimientos usando Natural Language Toolkit y luego implementando RNAs En este repositorio estaremos abordando el procesamiento de lenguaje natural (NLP) usando la librería 'nltk' de Python.
Esta nos permite hacer un análisis de los sentimientos de múltiples reseñas de películas tomadas de usuarios de la plataforma 'IMDb'.
Creando un tokenizador que permite separar las reseñas por frases, podemos asignar una polaridad a cada sentencia / frase de la reseña, se busca asignar polaridades usando el método SIA (Sentiment Intensity Analyzer).

Finalmente buscamos hacer una ponderación total de las sentencias para asignar un sentimiento dependiendo del valor ponderado de la reseña, para asignarlo a un sentimiento definido por una escala PANAS-t. 
Esta nos permite hacer un recorrido general sobre los sentimientos de los usuarios frente a diferentes películas que vieron.

Adicionalmente podemos encontrar un cuestionario resuelto a lo largo del Notebook el cual nos permite conocer más a profundidad otras incognitas que se pretenden abordar en el ejercicio.
Soportadas también con la implementación de Redes Neuronales Artificiales (RNAs) y gráficas como histogramas o gráficos polares haciendo uso de los módulos 'matplotlib' y 'seaborn'.


# Descripción del dataset
Nos encontramos con una base de datos 'Movie Reviews' en donde estaremos usando la hoja 'data' en donde encontramos apróximadamente 1.700 reseñas de películas hasta el año 2020 las cuales se dividen  en las siguientes columnas / variables

'year' = Año de estreno de la película.
'movie' = Nombre de la película
'rating' = Puntuación o calificación ponderada.
'helpful' = Indica cuantas veces la reseña fue de ayuda.
'total' =  Total de reacciones
'username' = Nombre de usuario de quien realiza la reseña.
'date' = Fecha de publicación de la reseña.
'title' = Título de la reseña.
'review' = Texto de la reseña.
