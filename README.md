# HENRY_PI_3_MOOCs-

## Datathon

# Descripción:
Este proyecto es un análisis de datos de cursos en línea (MOOCs). Se han importado tres conjuntos de datos diferentes de MOOCs de diferentes plataformas (edX, Coursera y Udemy) y se han limpiado y preprocesado para obtener información útil. Se han agregado nuevas columnas y se han realizado transformaciones en las columnas existentes para obtener una mejor comprensión de los datos. Finalmente, se ha concatenado todo en un solo conjunto de datos llamado "final_data" y se ha exportado tanto en formato .csv como en formato xlsx.

En este proyecto se ha utilizado la biblioteca pandas de Python para manipular y analizar los datos. También se ha utilizado la biblioteca langdetect para detectar el idioma de los títulos y las descripciones de los cursos.

La siguiente sección explicará los requisitos del sistema y cómo ejecutar el código

# Pipeline:
En esta sección se describirá el proceso llevado a cabo para limpiar y preprocesar los datos, así como la creación de los dataframes y la exportación de los mismos.

- Paso 1: Importación de los archivos originales.
- Paso 2: Limpieza de los datos. Se eliminaron filas con valores nulos y columnas innecesarias.
- Paso 3: Detección del idioma en las columnas "reviews" y "course_id" en el dataframe "coursera_reviews" y creación de la columna "language".
- Paso 4: Cambio de nombre a las columnas y modificación de los valores en las columnas "level".
- Paso 5: Agregación de la columna "institution" y reordenamiento de las columnas en los dataframes "udemy_courses" y "edx_courses".
- Paso 6: Cambio del tipo de datos de la columna "price" en el dataframe "coursera_clean".
- Paso 7: Concatenación de los dataframes "udemy_courses", "edx_courses" y "coursera_clean" en un dataframe final "final_data".
- Paso 8: Exportación de los dataframes a archivos .csv y .xlsx en la carpeta "./Datasets/Cleaned".

# Detalle de uso:
Por inconvenientes con el tamaño de archivos y carpetas, solo se puede disponer en github de aquello justo y necesario para correr el proyeto
En el link de drive se puede acceder al proyecto entero y la presentación de power BI

https://drive.google.com/drive/folders/1CTfT57fXwONuErVQekRGz2iMoiosuMBT?usp=sharing

# Sobre EDA en el proyecto:
En este proyecto, se realizó un análisis exploratorio de datos (EDA) en los datasets de cursos en línea recolectados de Coursera, Udemy y edX. Durante este proceso, se limpiaron y transformaron los datos para lograr una mejor comprensión de la información. Se identificaron y trataron valores faltantes y duplicados y se renombraron las columnas para una mejor legibilidad.

Además, se utilizó la librería langdetect para detectar el idioma de los títulos y materias de los cursos y se agregó una nueva columna "idioma" para reflejar esta información. Se realizó una agrupación de los cursos en función de su idioma y se visualizó la relación entre el idioma y la calificación de los cursos.

Este EDA permitió obtener una mejor comprensión de la información contenida en los datasets y establecer una base sólida para futuras investigaciones y análisis.

# KPI:

En esta sección, se describirá el indicador clave de desempeño (KPI) utilizado en el proyecto.

El KPI elegido para este proyecto es la relación entre el lenguaje y los cursos y la relación entre el lenguaje y la calificación de los cursos. Con esta información, la empresa podrá priorizar los cursos que están mejor calificados y el lenguaje y la institución de estos cursos también serán importantes para establecer las primeras iteraciones de la empresa en el mercado de MOOCs.

Además, a través de la exploración de los datos, se podrá identificar patrones y tendencias en la demanda de cursos y lenguajes específicos, lo que permitirá a la empresa tomar decisiones informadas sobre la oferta de cursos y la inversión en la adquisición de nuevos recursos y capacitaciones.

En resumen, el KPI elegido es una combinación de la relación entre el lenguaje, la calificación y la institución de los cursos, y permite a la empresa tener una visión completa de la demanda y la calidad de los cursos en el mercado de MOOCs.

# Conclusiones:
A través de la exploración de los datasets de cursos de Udemy, Coursera y edX, se logró identificar patrones y tendencias en el mercado de los MOOCs. Se identificó la relación entre el idioma y los cursos, así como también la relación entre el idioma y la calificación de los cursos.

Además, se realizó una limpieza exhaustiva de los datos para garantizar la precisión de los resultados obtenidos. A través de este proceso de limpieza, se eliminaron columnas innecesarias, se renombraron columnas para hacerlas más claras y se convirtieron los tipos de datos en los formatos adecuados.

Por último, se creó una KPI que permitiría a una empresa de MOOCs priorizar los cursos que están mejor calificados y cuya lengua y institución sean importantes para establecer las primeras iteraciones de su negocio.

En resumen, a través de este proyecto se logró obtener una comprensión más profunda del mercado de los MOOCs y se crearon herramientas útiles para guiar las decisiones empresariales futuras.
