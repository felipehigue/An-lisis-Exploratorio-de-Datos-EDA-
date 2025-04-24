# An-lisis-Exploratorio-de-Datos-EDA-
# Proyecto 1: Análisis Exploratorio de Datos de Redes Sociales

Este proyecto consiste en un análisis exploratorio de datos (EDA) de un dataset simulado de una red social. El objetivo principal es limpiar, explorar y visualizar los datos para identificar patrones, tendencias y obtener insights sobre la actividad de los usuarios y las interacciones en la plataforma.

## Dataset

El dataset utilizado es `social_media_sucio.csv`, un archivo CSV simulado que contiene información básica sobre publicaciones en una red social ficticia. Las columnas incluyen:

* `Usuario`: Nombre de usuario del autor de la publicación.
* `Fecha Publicación`: Fecha y hora en que se realizó la publicación.
* `Texto`: Contenido del mensaje de la publicación.
* `Likes`: Número de "me gusta" recibidos por la publicación.
* `Retweets`: Número de veces que la publicación fue compartida.
* `Idioma`: Idioma en el que se escribió la publicación.
* `Fuente`: Plataforma o dispositivo utilizado para publicar (e.g., Android, Web, iPhone).

## Objetivos del Proyecto

* Realizar la limpieza y el preprocesamiento del dataset para manejar inconsistencias y valores faltantes.
* Explorar la distribución de las variables clave (fuente, fecha de publicación, interacciones, idioma).
* Identificar posibles patrones o tendencias en la actividad de los usuarios y las interacciones.
* Visualizar los datos de manera efectiva para comunicar los hallazgos.

## Pasos Realizados

1.  **Carga de Datos:** El dataset `social_media_sucio.csv` fue cargado utilizando la biblioteca Pandas de Python.
2.  **Limpieza de Datos:** Se realizaron los siguientes pasos para limpiar y estandarizar el dataset:
    * Estandarización de los nombres de usuario (convertir a minúsculas, eliminar espacios, unificar separadores).
    * Conversión de la columna 'Fecha Publicación' a formato datetime.
    * Estandarización de los nombres de los idiomas (eliminación de tildes, conversión a minúsculas).
    * Manejo de valores faltantes (especificar cómo se manejaron, e.g., imputación o eliminación).
    * Verificación y ajuste de los tipos de datos de las columnas.
3.  **Análisis Exploratorio de Datos (EDA):** Se exploraron las siguientes características y relaciones:
    * Distribución de las fuentes de publicación.
    * Tendencia de publicaciones a lo largo de los días de la semana.
    * Distribución de la cantidad de 'Likes'.
    * Distribución de la cantidad de 'Retweets'.
    * [Aquí puedes añadir cualquier otro análisis específico que hayas realizado, como relaciones entre variables].
4.  **Visualizaciones:** Se utilizaron las bibliotecas Matplotlib y Seaborn para crear visualizaciones como gráficos de barras, histogramas y gráficos de línea para ilustrar la distribución de las variables y las posibles tendencias.
5.  **Conclusiones:** Se resumen los principales hallazgos y patrones observados durante el análisis. [Aquí puedes incluir un breve resumen de tus conclusiones principales, como la fuente de publicación más común, los días de mayor actividad, la distribución de las interacciones, etc.].

## Hallazgos Principales 
* La mayoría de las publicaciones provinieron de la fuente web.
* El día con mayor actividad de publicación fue viernes.
* La distribución de 'Likes' y 'Retweets' mostró un sesgo hacia izquierda, indicando que la mayoría de las publicaciones tienen baja interacción.
* [Añade cualquier otro hallazgo relevante de tu análisis].

## Limitaciones

* El dataset utilizado es simulado y relativamente pequeño, por lo que los patrones observados podrían no ser representativos de un dataset real de redes sociales a gran escala.
* El rango de fechas del dataset es limitado, lo que dificulta el análisis de tendencias a largo plazo.

## Próximos Pasos (Potenciales)

* Analizar el contenido del texto para identificar temas o palabras clave comunes.
* Realizar un análisis de sentimiento de las publicaciones.
* Explorar la relación entre múltiples variables simultáneamente.
* Aplicar técnicas de modelado para predecir la popularidad de las publicaciones.
* Analizar un dataset de redes sociales más grande y con un rango de fechas más amplio.

## Cómo Ejecutar el Código

1.  Asegúrate de tener instaladas las bibliotecas necesarias: Pandas, Matplotlib y Seaborn. Puedes instalarlas usando `pip install pandas matplotlib seaborn`.
2.  Guarda el archivo `social_mediamedia.xlsx` en el mismo directorio que tu script de Python o notebook de Colab.
3.  Ejecuta el script de Python o el notebook de Colab que contiene el código para el análisis.

## Autor
**Felipe Higuera tovar**



