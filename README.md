# Trabajo fin de Máster


## Evaluar las redes neuronales convolucionales para la clasificación de imágenes histológicas de cáncer de colon rectal mediante la transferencia de aprendizaje.

### Organización

* convnet: arquitecturas implementadas. VGG16, VGG19 e InceptionV3. Primero, se obtienen descriptores profundos, a los que se aplican primero reducción de dimensionalidad y luego se clasifican por métodos clásicos. Segundo, se entrena una capa convolucional en cada arquitectura y es la propia red quien clasifica las imágenes.

* data: exploración de los datos y la creación de muestras para el entrenamiento de la capa convolucional.

* system: información del sistema en el que se ha desarrollado el trabajo. Logs de algunas plataformas y programas usados.

Nota: Las imágenes y las muestras no se han incluido, por el tamaño de las mismas. En [J. N. Kather et al., “Collection of textures in colorectal cancer histology,” doi.org, May 2016](https://zenodo.org/record/53169/export/hx) pueden ser descargadas.

### Tecnologías

* Git-Github: para el versionado de código.
* Mendeley: para la organización de la bibliografía a la que se ha recurrido.
* Python - Jupyter: para la edición de código de las implementaciones llevadas a cabo.
* Keras - Anaconda: conjunto de librerías que se usarán en el desarrollo de la investigación.
