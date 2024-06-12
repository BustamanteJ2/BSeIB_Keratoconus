# BSeIB_Keratoconus
 Sistema de Detección de Queratocono con Inferencia Bayesiana.
 10056926 - BSeIB - Reporte Final
 Centro de Investigación en Ciencias. Universidad Autónoma del Estado del Morelos.

# Abstract
El presente reporte ilustra el proyecto “Sistema de diagnóstico de queratocono basado en inferencia bayesiana” aplicable al tercer parcial del
curso “Búsqueda de Soluciones e Inferencia Bayesiana” del programa educativo Licenciatura en Inteligencia Artificial, adscrito al Centro de
Investigación en Ciencias de la Universidad Autónoma del Estado de Morelos.
El proyecto propuesto consiste en desarrollar un clasificador bayesiano para el diagnóstico de queratocono, a partir de mapas topográficos
corneales (obtenidas en formato de imagen) etiquetadas como pacientes con queratocono, pacientes sospechosos de queratocono y pa-
cientes con ojos normales. La inferencia bayesiana es emplea con el fin de modelar la probabilidad de la presencia de queratocono con base
en las características de las imágenes. Los resultados preliminares muestran una precisión del XX% en la detección de queratocono, lo que
sugiere la viabilidad de utilizar este enfoque para el diagnóstico temprano de la enfermedad.

> Keywords: Clasificador Bayesiano, Queratocono, Inferencia Bayesiana, mapas topográficos corneales, Diagnóstico

# Estructura del proyecto:

> **Train_Validation sets**: Carpeta con los mapas topográficos corneales para el entrenamiento del modelo.
> **Independent Test Set**: Carpeta con los mapas topográficos corneales para la validación del modelo.
> **10056926-BSeIB-Recurso.ipynb**: Notebook de Python donde se detalla código de apoyo para obtener las direcciones path relativas de los mapas topográficos corneales almacenados en ambas carpetas (mencionadas con anterioridad).
> **independent_test_path.csv**: Archivo CSV resultante de la ejecución de ‘10056926-BSeIB-Recurso.ipynb’. Alberga las rutas path relativas de las los mapas topográficos corneales almacenados en la carpeta Independent Test Set.
> **train_validation_path.csv**: Archivo CSV resultante de la ejecución de ‘10056926-BSeIB-Recurso.ipynb’. Alberga las rutas path relativas de las los mapas topográficos corneales almacenados en la carpeta Train_Validation sets.
> ** 10056926-BustamanteJ-BSeIB-Proy.ipynb**: Notebook de Python donde se realiza el “Sistema de diagnóstico de queratocono basado en inferencia bayesiana”. 


