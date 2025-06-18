# Brecha Salarial de Género en Argentina

## Descripción general

Este proyecto analiza la evolución de la remuneración media del empleo registrado en el sector privado en Argentina, según rama de actividad (CIIU Rev. 3) y género, entre enero de 1996 y octubre de 2022. Utilizando herramientas de ciencia de datos y modelos de aprendizaje supervisado, se identifican patrones, desigualdades y tendencias vinculadas a la brecha salarial de género en el mundo laboral formal.

## Objetivo general

Analizar la evolución de la remuneración media del empleo registrado en el sector privado en Argentina, según rama de actividad y género, utilizando herramientas de data science, con el fin de identificar patrones, desigualdades y tendencias vinculadas a la brecha salarial de género.

## Objetivos específicos

- Procesar y limpiar el conjunto de datos proporcionado, utilizando bibliotecas como `pandas` para su análisis exploratorio.
- Describir la evolución temporal de la remuneración media por género y rama de actividad (CIIU rev. 3 a dos dígitos).
- Comparar trayectorias salariales entre varones y mujeres, identificando sectores con mayores y menores brechas.
- Visualizar los resultados mediante gráficos que faciliten la comprensión de las desigualdades.
- Aplicar modelos de regresión supervisada para predecir la remuneración media en función del género, la industria y el período.
- Reflexionar sobre las implicancias sociales y económicas de las desigualdades de género en el ámbito laboral formal.

## Contenido del repositorio

- `Remuneraciones.csv`: base de datos original con información de remuneraciones por género, industria y período.
- `genero_clasificacion.ipynb`: notebook con modelos de clasificación para predecir el género en función de variables económicas.
- `remuneracion_regresion.ipynb`: notebook con modelos de regresión para predecir el valor de la remuneración.
- `README.md`: este archivo.

# Instalación y requisitos
- Instalar Visual Studio Code o Anaconda desde su respectiva web.
- Instalar Python desde su web.
- Independientemente del espacio elegido para trabajar, instalar las librerias pandas, numpy, seaborn, matplotlib y scikit-learn.
- Clonar el repositorio [https://github.com/jorgelinasigal/datascience.git].
- Abrir la carpeta tercera pre-entrega en el entorno.
- Ejecutar las celdas en orden para comenzar el análisis.
  
## Herramientas utilizadas
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Metodología

Se implementaron dos enfoques de aprendizaje supervisado:

1. **Clasificación**: predicción del género a partir de variables como remuneración, industria y decil.  
   Se evaluaron métricas como:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Matriz de confusión

2. **Regresión**: predicción de la remuneración media según género, rama y período.  
   Se evaluaron métricas como:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² (Coeficiente de determinación)

Además, se realizaron procesos de **optimización de hiperparámetros** mediante técnicas como GridSearchCV y validación cruzada.

## Principales resultados

- Se evidencian brechas salariales persistentes a lo largo del tiempo, con variaciones según el sector.
- Algunas ramas de actividad presentan mayores niveles de desigualdad entre géneros.
- Los modelos permiten identificar patrones, aunque presentan limitaciones para tareas predictivas más finas.

## Reflexión final

El análisis pone de manifiesto desigualdades estructurales en el mercado laboral argentino, que afectan de manera diferenciada a varones y mujeres. Si bien los modelos de aprendizaje supervisado aportan información valiosa, se reconoce la importancia de contextualizar los resultados y no perder de vista el enfoque crítico y ético en el análisis de datos sociales.

## Autoría

Proyecto realizado por **Jorgelina Sigal** y **Daniela Ferraro** (2025). 
[www.linkedin.com/in/jorgelina-sígal-014855217] [www.linkedin.com/in/danielamilagrosferraro] 
