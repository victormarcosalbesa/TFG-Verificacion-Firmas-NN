# Modelos entrenados

Los modelos entrenados no se almacenan directamente en el repositorio debido a su tamaño.

Se encuentran disponibles en la sección de Releases:

- Release: `v1.0-modelos-entrenados`

## Modelos incluidos

| Modelo | Tipo | Descripción |
|---|---|---|
| `MLP_SGD_SinDropout.pt` | MLP | MMLP entrenada con el algoritmo SGD sin Dropout |
| `cnn_augmentation.pt` | CNN | CNN entrenada con aumento de datos |
| `cnn_dropout.pt` | CNN | CNN con regularización Dropout |
| `cnn_final.pt` | CNN | Modelo final utilizado en la aplicación móvil |
| `mlp_baseline.pt` | MLP | Modelo MLP inicial |
| `mlp_dropout.pt` | MLP | MLP con Dropout |
| `mlp_tuned.pt` | MLP | MLP con ajuste de hiperparámetros |
| `mlp_final.pt` | MLP | Mejor modelo MLP obtenido |
