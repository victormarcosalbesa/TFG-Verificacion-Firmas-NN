# Dataset

Esta carpeta contiene los archivos relacionados con la creación y documentación del dataset utilizado en el entrenamiento de los modelos de clasificación de imágenes del TFG.

El dataset se construyó a partir de firmas recogidas mediante una plantilla diseñada específicamente para este proyecto.

## Contenido de la carpeta

| Archivo                   | Descripción                                                                                                               |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| `plantilla_firmas.pdf`     | Plantilla utilizada para la recolección de firmas.                                                                        |
| `extraccion_imagenes_dataset.ipynb` | Notebook utilizado para extraer automáticamente las firmas desde el PDF original y guardarlas como imágenes individuales. |

## Archivos disponibles en Releases

Debido a su tamaño, los archivos principales del dataset no se almacenan directamente en el repositorio, sino en la sección de **Releases**.

La release del dataset incluye:

| Archivo                     | Descripción                                                         |
| --------------------------- | ------------------------------------------------------------------- |
| `DATASET.pdf`     | Documento PDF con todas las firmas recogidas mediante la plantilla. |
| `IMAGENES_DEF.zip` | Dataset final utilizado durante el entrenamiento de los modelos.    |

## Proceso de creación del dataset

El proceso seguido para construir el dataset fue el siguiente:

1. Se diseñó una plantilla vacía para facilitar la recogida de firmas.
2. La plantilla fue rellenada manualmente con las firmas.
3. Las hojas con firmas fueron agrupadas en un único documento PDF.
4. Mediante el notebook `extraccion_imagenes_dataset.ipynb`, se extrajeron las firmas del PDF original y se guardaron como imágenes individuales.
5. Las imágenes extraídas fueron procesadas posteriormente para construir el dataset final utilizado en el entrenamiento.

## Diferencia entre las imágenes extraídas y el dataset final

El notebook `extraccion_firmas.ipynb` extrae las firmas desde el PDF original y genera imágenes individuales con fondo blanco y trazo negro.

Sin embargo, el dataset final utilizado durante el entrenamiento no corresponde exactamente a esas imágenes extraídas directamente. Antes del entrenamiento, las imágenes fueron transformadas para presentar fondo negro y trazo blanco.

Por tanto:

* Las imágenes extraídas por el notebook son una versión intermedia del proceso.
* El archivo `IMAGENES_DEF.zip` contiene la versión final utilizada para entrenar los modelos.
* El dataset final presenta fondo negro y trazo blanco, formato empleado durante el entrenamiento de los modelos CNN y MLP.

Este material se proporciona con fines académicos dentro del Trabajo de Fin de Grado.
