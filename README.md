# Visión por Computadora 3D

Trabajos prácticos de la materia Visión por Computadora 3D, Maestría en Inteligencia Artificial (FIUBA).

## Tarea 1: Clasificación de frutas con Depth Estimation y CNN 3D

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/antonellagambarte/vision3D/blob/main/Tarea_1,_Clasificaci%C3%B3n_de_frutas_con_Depth_Estimation_y_CNN_3D.ipynb)

Notebook: [Tarea_1,_Clasificación_de_frutas_con_Depth_Estimation_y_CNN_3D.ipynb](Tarea_1,_Clasificaci%C3%B3n_de_frutas_con_Depth_Estimation_y_CNN_3D.ipynb)

A partir de fotos de frutas de Fruits-360 se estima la profundidad con Depth Anything V2, cada foto se convierte en una nube de puntos con el modelo pinhole y se voxeliza para clasificarla con una CNN 3D (solo forma, y forma y color). Los resultados se comparan con una CNN 2D que mira directamente la foto.
