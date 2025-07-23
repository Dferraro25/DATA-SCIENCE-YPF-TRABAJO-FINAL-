# Brecha Salarial de Género en Argentina

## Descripción general

Este proyecto analiza la evolución de la remuneración media del empleo registrado en el sector privado en Argentina entre enero de 1996 y octubre de 2022, diferenciando por rama de actividad (CIIU Rev. 3) y género. A través de herramientas de ciencia de datos, se aplica tanto aprendizaje supervisado (regresión) como no supervisado (clustering) para identificar patrones, desigualdades y segmentaciones salariales en el mundo laboral formal.

## Objetivo general

Analizar la evolución de la remuneración media del empleo registrado en el sector privado en Argentina, según rama de actividad y género, utilizando herramientas de data science, con el fin de identificar patrones, desigualdades y tendencias vinculadas a la brecha salarial de género.

## Objetivos específicos

- Procesar y limpiar el conjunto de datos proporcionado, utilizando bibliotecas como `pandas` para su análisis exploratorio.
- Describir la evolución temporal de la remuneración media por género y rama de actividad (CIIU rev. 3 a dos dígitos).
- Comparar trayectorias salariales entre varones y mujeres, identificando sectores con mayores y menores brechas.
- Visualizar los resultados mediante gráficos que faciliten la comprensión de las desigualdades.
- Aplicar modelos de aprendizaje supervisado para predecir la remuneración media en función del género, la industria y el período.
- Aplicar modelos de clustering para segmentar perfiles salariales y descubrir agrupamientos naturales sin etiquetas previas.
- Determinar el número óptimo de clusters mediante el método del codo y Silhouette Score.
- Reflexionar sobre las implicancias sociales y económicas de las desigualdades de género en el ámbito laboral formal a partir de los hallazgos obtenidos.

## Contenido del repositorio

- `Remuneraciones.csv`: base de datos original con información de remuneraciones por género, industria y período.
- `remuneracion_clustering.ipynb`: notebook con modelo de clustering.
- `README.md`: este archivo.

## Instalación y requisitos

- Instalar Visual Studio Code o Anaconda desde su respectiva web.
- Instalar Python desde su web.
- Independientemente del espacio elegido para trabajar, instalar las librerias pandas, numpy, seaborn, matplotlib y scikit-learn.
- Clonar el repositorio [https://github.com/jorgelinasigal/datascience.git].
- Abrir la carpeta tercera pre-entrega en el entorno.
- Ejecutar las celdas en orden para comenzar el análisis.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Metodología

Se implementó un modelo de aprendizaje no supervisado con los siguientes pasos:

    - Tratamiento de outliers con IQR y Robust Scaler.
    - Aplicación de algoritmo K-means.
    - Aplicación del método del codo.
    - Aplicación de Silhouette Score.
    - Visualización mediante PCA.

## Principales resultados

- Se evidencias brechas salarias persistentes entre varones y mujeres.
- La variable 'Industria' es la más influyente a la hora de predecir los salarios.
- Se detectó una cantidad significativa de outliers salariales que no fueron eliminados, sino tratados para preservar el objetivo inicial del proyecto.

## Reflexión final

Los resultados reflejan una realidad estructural en la que las mujeres tienden a percibir remuneraciones más bajas, aún dentro del mismo período y sector. Se destaca la importancia de contextualizar los modelos dentro de un análisis ético y socialmente consciente, entendiendo que el valor del análisis de datos va más allá de lo técnico: *contribuye a visibilizar problemáticas sociales profundas y orientar políticas más justas.*

## Autoría

Proyecto realizado por **Jorgelina Sigal** y **Daniela Ferraro** (2025). 
[www.linkedin.com/in/jorgelina-sígal-014855217] [www.linkedin.com/in/danielamilagrosferraro] 