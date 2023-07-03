# Dataset de detección de delitos en el transporte público

Este repositorio contiene un conjunto de datos de imágenes relacionadas con delitos en el transporte público. El dataset está diseñado para la detección de diferentes categorías de incidentes.

## Estructura de carpetas

- **annotations**: Contiene los archivos XML en formato PASCAL VOC con las anotaciones de las imágenes.
- **images**: Contiene los archivos de imagen en formato JPG.
- **raccoon_classes.txt**: Archivo de texto que contiene las clases de objetos. En este caso, las categorías son:
    - 1: Barricade
    - 2: Incident Bus/Bus station
    - 3: Incident Subway
- **raccoon_test.txt**: Archivo de texto que contiene la lista de imágenes seleccionadas para el conjunto de prueba.
- **raccoon_train.txt**: Archivo de texto que contiene la lista de imágenes seleccionadas para el conjunto de entrenamiento.
- **raccoon_train_data.txt**: Archivo de descripción personalizado para el conjunto de entrenamiento, con un registro por cada imagen. El formato de cada registro es: ruta_de_imagen caja1 caja2 ... cajaN. El formato de cada caja es: x_min,y_min,x_max,y_max,identificador_clase (sin espacios).
- **raccoon_test_data.txt**: Archivo de descripción personalizado para el conjunto de prueba, con un registro por cada imagen, siguiendo el mismo formato que el archivo de entrenamiento.

## Uso del dataset

Puedes utilizar este dataset para entrenar y evaluar modelos de detección de delitos en el transporte público. Las imágenes y las anotaciones están disponibles para su procesamiento.

¡Disfruta trabajando con el dataset y buena suerte en tus experimentos!
