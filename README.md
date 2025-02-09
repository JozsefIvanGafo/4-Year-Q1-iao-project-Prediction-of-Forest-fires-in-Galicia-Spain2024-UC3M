# iao-project-2024
El código de la práctica se ha realizado utilizando Jupyter Notebook, por lo que se incluyen los archivos en formato ipynb, así como los ficheros con los datos en csv.
Para la reproducción de resultados se explica brevemente su contenido:

- Carpeta data: Contiene todos los datos utilizados para la resolución del proyecto. Se incluyen tanto los datos del número de incendios y superficie quemada, como los datos meteorológicos de todos los años, que se utilizarán en el preprocesado. También se incluyen los resultados del preprocesado en los archivos "fires-time-series.csv", "fires-weather.csv" y "fires_weather_timeseries".

- requirement.txt: Fichero que contiene las librerías requeridas para la ejecución del proyecto.
preprocessing.ipynb: Notebook de Jupyter que realiza las labores de preprocesado de los datos, añadiendo los datos meteorológicos como variables exógenas. Este fichero debe ejecutarse anteriormente al resto de notebooks para que puedan trabajar con los datos ya procesados.

- prediction_time_series.ipynb: Notebook de Jupyter que contiene el código para crear los modelos y realizar las predicciones utilizando series temporales. Además, el código generará las gráficas expuestas en el apartado de "Evaluación".

- prediction_exogenous_vars: Notebook de Jupyter que contiene el código para crear los modelos y realizar las predicciones utilizando variables exógenas. Además, el código generará las gráficas expuestas en el apartado de "Evaluación".

En todos los procesos de entrenamiento se utiliza una semilla (42) para permitir reproducir los resultados obteniendo las mismas métricas.
Es posible que se tenga que actualizar el path de algunas lecturas para acceder a los archivos dependiendo de las rutas de los ficheros de sus ordenadores.
