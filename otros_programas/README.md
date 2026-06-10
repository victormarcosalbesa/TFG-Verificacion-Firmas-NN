# Otros programas

Esta carpeta contiene programas auxiliares desarrollados durante el Trabajo de Fin de Grado.

Estos notebooks no forman parte directamente del entrenamiento principal de los modelos CNN y MLP, pero se han utilizado como apoyo para explicar, visualizar o comparar conceptos relacionados con las redes neuronales y el procesamiento de imágenes.

## Contenido de la carpeta

| Archivo | Descripción |
|---|---|
| `funciones_de_activacion.ipynb` | Notebook que representa gráficamente distintas funciones de activación utilizadas en redes neuronales. |
| `comparativa_de_algoritmos_de_descenso.ipynb` | Notebook que compara distintos algoritmos de descenso aplicados a un ejemplo de regresión lineal mal condicionado. |
| `ejemplo_de_convolucion.ipynb` | Notebook que muestra un ejemplo práctico de convolución sobre una imagen del dataset, aplicando un filtro de detección de bordes y una operación de Max-Pooling. |

## Descripción de los programas

### Funciones de activación

El notebook `funciones_de_activacion.ipynb` genera gráficas comparativas de funciones de activación utilizadas habitualmente en redes neuronales.

Este programa sirve como apoyo visual para comprender el comportamiento de funciones como Sigmoid, Tanh, ReLU u otras funciones relacionadas con el aprendizaje profundo.

### Comparativa de algoritmos de descenso

El notebook `comparativa_de_algoritmos_de_descenso.ipynb` realiza una comparación entre distintos algoritmos de descenso estudiados en el trabajo.

El ejemplo se basa en un problema de regresión lineal bidimensional mal condicionado, lo que permite observar diferencias en el comportamiento y la convergencia de los métodos analizados.

### Ejemplo de convolución

El notebook `ejemplo_de_convolucion.ipynb` aplica una operación de convolución sobre una imagen del dataset.

En concreto, utiliza un filtro de detección de bordes Laplaciano y posteriormente aplica una operación de Max-Pooling, reduciendo el tamaño de la imagen. Este programa sirve para ilustrar de forma práctica operaciones habituales en redes neuronales convolucionales.
