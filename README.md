# LN-Actividad-Integradora-3

Activiad Integradora #3
Integrantes del equipo:  María Fernanda Mendoza, Isis María Camila Muñoz Salamanca, Mauricio Náñez Pro, David Martín Oliva Zavala y Carolina Obregón.

Intrucciones:
-Descargar los archivos incluidos en el repositorio
-Abrir el archivo principal "RNN.ipynb" notebook collab desde el repositorio
-Incluir los archivos descargados al Google Collab
-Ejecutar las celdas

Contenido del archivo:
Este programa es capaz de realizar un análisis de sentimientos en base a diferentes segmentos de información de diferente redes sociales como Twitter, Reddit y 
comentarios de de Youtube.

Se descargó una base de datos de reseñas de peliculas de IMDB la cual se limpió y organizo para poder realizar un entrenamiento con diferentes arquitecturas
e inclusive incluye la arquitectura de BERT, una red bidreccional efectiva para esta caso que queremos categorizar los textos en negativos, neutrales y positivos.

Al finalizar, se obtiene una base de datos de 2 redes sociales diferentes las cuales nos ayudan para poder hacer un test de nuestro modelo.

Para la parte de innovar e incorporar funciones adicionales, realizamos el incluir más redes sociales, diseñar un modelos que clasifica más de 2 tipos de sentimientos, también diseñamos nuestra propia base de datos y como extra  incorporamos el modelo avanzado Bert, se anexó al final y nos basamos en un proyecto el cual ya tenía los archivos del modelo, este nos brindó los hiperparámetros, pesos y tenía un entrenamiento previo, específicamente utilizamos el Bert-base uncased, al final en la parte de entrenar al modelo se requiere correr en terminal la sentencia de código mencionada, así mismo cuando se ejecuta la predicción, al final nos arrojará un archivo  test_results.tsv con todas las predicciones. 
