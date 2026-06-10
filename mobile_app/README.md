# Aplicación móvil

Esta carpeta contiene la información relativa a la aplicación móvil desarrollada para implementar el modelo de clasificación de imágenes entrenado durante el TFG.

La aplicación ha sido creada utilizando **Android Studio** y permite utilizar el modelo entrenado desde un dispositivo móvil Android.

## Descripción

La aplicación móvil integra el modelo de clasificación de imágenes desarrollado en el proyecto. Su objetivo es permitir que el usuario pueda seleccionar o capturar una imagen y obtener una predicción generada por el modelo entrenado.

Esta aplicación representa la parte práctica del sistema, demostrando cómo el modelo de inteligencia artificial puede ser utilizado fuera del entorno de entrenamiento.

## Tecnología utilizada

* **Android Studio**
* **Android**
* Modelo entrenado de clasificación de imágenes
* Integración del modelo dentro de una aplicación móvil

## Funcionalidades principales

* Carga o captura de imágenes desde el dispositivo.
* Procesamiento de la imagen para adaptarla al formato requerido por el modelo.
* Ejecución del modelo entrenado.
* Visualización del resultado de la clasificación.
* Interfaz sencilla orientada al uso práctico del sistema.

## Archivo de instalación

La aplicación móvil no se almacena directamente en esta carpeta.

El archivo instalable de la aplicación se encuentra disponible en la sección de **Releases** del repositorio.

Ejemplo:

```text
v1.0-aplicacion-movil
```

Dentro de esa release se incluye el archivo APK generado desde Android Studio.

## Uso

Para instalar la aplicación:

1. Descargar el archivo `.apk` desde la sección de Releases.
2. Transferirlo al dispositivo Android, si fuera necesario.
3. Permitir la instalación de aplicaciones de origen externo.
4. Instalar el APK.
5. Abrir la aplicación y utilizarla para realizar predicciones sobre imágenes.

## Relación con el modelo

La aplicación utiliza el modelo final entrenado durante el desarrollo del TFG.

Los modelos entrenados se encuentran documentados en la carpeta `models/` y disponibles en la sección de Releases del repositorio.

## Nota

Esta aplicación ha sido desarrollada con fines académicos como parte del Trabajo de Fin de Grado.
