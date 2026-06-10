# Redes neuronales aplicadas a la verificación de firmas manuscritas

Este repositorio contiene el código, los resultados y los recursos asociados al Trabajo de Fin de Grado basado en la clasificación de imágenes de firmas mediante modelos de aprendizaje profundo.

El proyecto compara distintas arquitecturas de redes neuronales, principalmente modelos CNN y MLP, entrenadas sobre un dataset propio de imágenes de firmas. Además, se ha desarrollado una aplicación móvil Android que implementa el modelo entrenado.

## Contenido del repositorio

```text
.
├── dataset/
│   ├── README.md
│   ├── extraccion_imagenes_dataset.ipynb
│   └── plantilla_firmas.pdf
│
├── mobile_app/
│   └── README.md
│
├── models/
│   └── README.md
│
├── notebooks/
│   ├── Comparativa_Redes_Firmas.ipynb
│   └── README.md
│
├── results/
│   ├── README.md
│   ├── comparativa_barras.png
│   ├── comparativa_biometrica.csv
│   ├── comparativa_global.png
│   └── comparativa_subplots.png
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Descripción del proyecto

El objetivo del proyecto es desarrollar y evaluar modelos capaces de clasificar imágenes de firmas. Para ello, se ha creado un dataset propio a partir de firmas recogidas mediante una plantilla diseñada específicamente para este trabajo.

Posteriormente, las firmas fueron extraídas automáticamente desde un documento PDF y procesadas para obtener imágenes individuales con fondo negro y trazo blanco. Estas imágenes fueron utilizadas para entrenar y evaluar diferentes modelos de clasificación.

## Modelos utilizados

Durante el desarrollo del proyecto se entrenaron y compararon distintos modelos, incluyendo:

- Redes neuronales convolucionales, CNN.
- Redes neuronales multicapa, MLP.

Los modelos fueron evaluados mediante métricas de rendimiento y gráficas comparativas, con el objetivo de seleccionar el modelo más adecuado para su integración en la aplicación móvil.

## Estructura del repositorio

### `notebooks/`

Contiene el notebook principal del proyecto:

- `Comparativa_Redes_Firmas.ipynb`: notebook utilizado para entrenar, evaluar y comparar los modelos CNN y MLP.

### `dataset/`

Contiene los archivos relacionados con la creación del dataset:

- `plantilla_firmas.pdf`: plantilla utilizada para la recogida de firmas.
- `extraccion_imagenes_dataset.ipynb`: notebook utilizado para extraer las firmas desde el PDF original y aplicar el procesamiento necesario.

Los archivos pesados del dataset se encuentran disponibles en la sección de Releases.

### `results/`

Contiene las gráficas y la tabla de resultados obtenidas durante la evaluación de los modelos.

### `models/`

Contiene la documentación relativa a los modelos entrenados.

Los archivos `.pt` de los modelos no se almacenan directamente en el repositorio, sino en la sección de Releases.

### `mobile_app/`

Contiene la documentación relativa a la aplicación móvil Android desarrollada con Android Studio.

El archivo instalable de la aplicación se encuentra disponible en la sección de Releases.

## Releases

Los archivos pesados del proyecto se encuentran disponibles en la sección de Releases del repositorio.

### Aplicación móvil

Contiene el archivo `.apk` de la aplicación Android desarrollada para implementar el modelo entrenado.

### Modelos entrenados

Contiene los modelos `.pt` entrenados durante el proyecto, incluyendo modelos CNN y MLP.

### Dataset

Contiene los archivos principales del dataset:

- `DATASET.pdf`: documento PDF con las firmas recogidas.
- `IMAGENES_DEF.zip`: dataset final utilizado durante el entrenamiento.

## Instalación

Para ejecutar los notebooks del proyecto, se recomienda crear un entorno de Python e instalar las dependencias mediante:

```bash
pip install -r requirements.txt
```

El archivo `requirements.txt` contiene las librerías necesarias para ejecutar los notebooks principales del proyecto.

## Dependencias principales

El proyecto utiliza, entre otras, las siguientes librerías:

- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SciPy
- OpenCV
- Pillow
- PyMuPDF
- Jupyter Notebook

## Autor

Víctor Marcos Albesa

Trabajo de Fin de Grado
