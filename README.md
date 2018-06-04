# Filtro bokeh basado en la segmentación fondo/figura
Trabajo realizado para la asignatura de PID (Procesamiento de Imágenes Digitales) de la Universidad de Sevilla.

Realizado por:
* frapercan
* STarrio
* angfra95


Diseño de un algoritmo que, dada una imagen sin profundidad de campo, genere un efecto visual similando al filtro bokeh, que realiza un difuminado en función de la distancia. Para ello se realizarán dos grandes pasos diferenciados: el primero será la separación entre el fondo y la figura de una imagen, para tratar de aproximar las relaciones de profundidad entre los distintos elementos de la imagen. Con esta aproximación se aplicará un algoritmo de simulación del filtro bokeh.

Basado en los papers:
* http://www.sciencedirect.com/science/article/pii/S0262885616301238
* https://otik.uk.zcu.cz/bitstream/11025/11225/1/Cyril.pdf

Basado en el código de:
* Algoritmo Meanshift (mattnedrich): https://github.com/mattnedrich/MeanShift_py

# English Version
# Bokeh filter based on foreground/background segmentation
Work done for the subject of PID (Digital Image Processing) for the University of Seville.

Code by:
* frapercan
* STarrio
* angfra95

Given an image without depth of field, we've designed an algorithm inspired in the following papers that generates a visual effect like bokeh filter. This filter makes a blur based on the distance. This algorithm has two steps:
* First, we've separated the foreground from the background to estimate the depth of field relationships between the different elements of the image.
* Secondly, with that approximation, we apply an algorithm which simulates the bokeh filter.

Based on the papers:
* http://www.sciencedirect.com/science/article/pii/S0262885616301238
* https://otik.uk.zcu.cz/bitstream/11025/11225/1/Cyril.pdf

Based on the code:
* Meanshift Algorithm (mattnedrich): https://github.com/mattnedrich/MeanShift_py
