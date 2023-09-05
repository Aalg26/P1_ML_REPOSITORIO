## Proyecto de Análisis de Datos de Juegos y Usuarios

Este proyecto de análisis de datos se centra en el estudio de la interacción entre usuarios y juegos en la plataforma Steam.
El proyecto se compone de tres carpetas principales y cinco archivos de Python, cada uno desempeñando un papel crucial en el procesamiento
y análisis de datos.🎮📊

## Estructura de Carpetas📂

**raw data**: Esta carpeta alberga los archivos de datos crudos en formato JSON. Estos archivos sirven como fuente de datos originales
para el proyecto.📂

**dataset**: Aquí se encuentran los datos que han sido procesados y preparados para su análisis. Los archivos CSV resultantes son utilizados
como insumo para diversas tareas de análisis.📂

**datasetAPI**: Esta carpeta contiene los datos específicos que la API utiliza para proporcionar respuestas a las solicitudes de los
 usuarios. Estos datos son fundamentales para la funcionalidad de la API.📂

## Archivos de Python 🐍

**API's_csv**: En este archivo se describe el proceso paso a paso utilizado para crear los archivos CSV que alimentan la API. Se detalla 
la limpieza, transformación y estructuración de los datos para su posterior uso.📄

**dummies_csv**: Aquí se encuentra la metodología empleada para generar un DataFrame con información sobre los usuarios y sus preferencias
por género en formato dummy. Este proceso es esencial para el análisis de gustos y recomendaciones.📄

**matriz_recomendacion**: Este archivo explica cómo se crea una matriz de recomendación utilizando la técnica de Descomposición de Valor 
Singular (SVD). Esta matriz es fundamental para la generación de recomendaciones personalizadas.📄

**EDA**: El archivo EDA contiene el proceso de Análisis Exploratorio de Datos. Aquí se exploran los datos, se realizan visualizaciones y 
se extraen insights para comprender mejor el conjunto de datos.📄

**ETL**: Este archivo detalla el proceso de Extracción, Transformación y Carga de datos (ETL). Se describe cómo se obtienen los datos de 
origen, se aplican transformaciones y se preparan para su uso en análisis posteriores.📄

## Main.py - API de Datos

El archivo main.py contiene el código de la API web desarrollada con FastAPI. Esta API ofrece endpoints para consultar y analizar datos
 relacionados con juegos y usuarios. También incorpora un modelo de recomendación basado en SVD para proporcionar recomendaciones 
 personalizadas a los usuarios.🌐

Este proyecto combina la ciencia de datos con la creación de una API interactiva para brindar a los usuarios la capacidad de explorar 
y obtener información valiosa sobre los datos de Steam. La estructura organizativa y los archivos de Python detallan cada paso del proceso 
de análisis de datos, desde la obtención de datos crudos hasta la generación de recomendaciones.🚀📈
