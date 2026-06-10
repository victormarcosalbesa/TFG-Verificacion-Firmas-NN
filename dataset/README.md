# Dataset

Esta carpeta contiene los archivos relacionados con la creación y documentación del dataset utilizado en el entrenamiento de los modelos de clasificación de imágenes del TFG.

El dataset se construyó a partir de firmas recogidas mediante una plantilla diseñada específicamente para este proyecto.

## Contenido de la carpeta

| Archivo                   | Descripción                                                                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `plantilla_firmas.pdf`     | Plantilla utilizada para la recolección de firmas.                                                                                                         |
| `extraccion_imagenes_dataset.ipynb` | Notebook utilizado para extraer automáticamente las firmas desde el PDF original, guardarlas como imágenes individuales y aplicar la inversión de colores. |

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
5. El propio notebook aplica una inversión de colores sobre las imágenes extraídas.
6. Las imágenes resultantes, con fondo negro y trazo blanco, forman el dataset final utilizado durante el entrenamiento.

## Transformación de las imágenes

Las firmas originales procedentes del PDF presentan fondo blanco y trazo negro.

Durante el procesamiento realizado en el notebook, se aplica una inversión de colores para obtener imágenes con:

* Fondo negro.
* Trazo blanco.
* Formato individual por firma.

Este formato es el utilizado posteriormente para entrenar y evaluar los modelos CNN y MLP.

## Dataset utilizado en el entrenamiento

El archivo `IMAGENES_DEF.zip`, disponible en la release del dataset, contiene las imágenes finales utilizadas durante el entrenamiento de los modelos.

Estas imágenes corresponden al resultado del proceso de extracción y transformación realizado sobre el PDF original de firmas.
