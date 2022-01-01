# Práctica 2: Dataset_analysis

Este proyecto es una práctica realizada por:<br>

EVGENY MUZAREV GEVORGIAN<br>
PABLO CHILLERÓN BEVIÁ<br>

para la asignatura M2.851 Tipología y ciclo de vida de los datos, dentro del Máster Oficial en Ciencia de Datos en la Universitat Oberta de Catalunya.<br>

## Descripción

Se trata de un proyecto en R para obtener, limpiar y analizar los datos de un dataset que contiene información sobre más de 20.000 recetas de todo el mundo, con el fin de analizar ciertas creencias sobre ciertos régimenes alimenticios y sobre ciertas relaciones entre valores nutritivos. Esta información es valiosa para cualquier persona, en particular, para aquellos que, por ejemplo, estén interesados en analizar estos datos antes de abrir un restaurante.<br>

## Archivos
Existen los sigueintes ficheros:<br>


1) <b>Archivo txt</b><br>
Archivos de texto en formato txt:<br>

epi_r.txt: fichero de texto con el enlace al csv con los datos iniciales. El fichero es superior a 25Mb, por lo que no es posible cargarlo en el proyecto.
Se puede encontrar este último fichero en Kaggle:<br><br>

Título: Epicurious - Recipes with Rating and Nutrition<br>
Subtítulo: Recipes from Epicurious by rating, nutritional content, and categories<br>
Visibilidad: público<br>
Dueño del set de datos: HugoDarwood<br>
Link al dataset: https://www.kaggle.com/hugodarwood/epirecipes<br>


2) <b>Archivos csv</b><br>
Dataframes en formato csv:<br>

epi_r-clean.csv: Dataframe con los datos del dataset tras la limpieza<br>

3) <b>Archivos rmd</b><br>
Archivos rmarkdown:<br>

Practica_2.Rmd: Fichero con el código y los comentarios respondiendo a las cuestiones de la práctica.

4) <b>Archivos HTML</b><br>
Archivos en formato HTML:<br>

Practica_2.html: Version HTML del fichero rmd, con el fin de mostrar los resultados tanto del código como de las cuestiones de la práctica en formato web.


## Librerías necesarias<br>
library(dplyr)<br>

