Laboratorio | Introducción al aprendizaje no supervisado
Instrucciones
Es el momento de realizar la agrupación de las canciones que has recopilado. Recuerda que el objetivo final de este pequeño proyecto es mejorar las recomendaciones de artistas. La agrupación de las canciones permitirá que el sistema de recomendaciones limite el alcance de las recomendaciones únicamente a las canciones que pertenecen al mismo grupo (canciones con características de audio similares).

Los experimentos que realizaste con la SpotifyAPI y el web scraping de Billboard te permitirán crear un pipeline tal que cuando el usuario ingrese una canción, tú:

Comprueba si la canción está o no en el Billboard Hot 200.
Recopila las funciones de audio de la SpotifyAPI.
Después de eso, desea enviar las Spotifycaracterísticas de audio de la canción enviada al modelo de agrupamiento, que debería devolver un número de grupo.

Queremos tener tantas canciones como sea posible para crear el modelo de agrupamiento, por lo que agregaremos las canciones que recopiló a un conjunto de datos más grande disponible en Kaggle que contiene 160 mil canciones.
