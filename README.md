# 🚖 Chicago Taxi Data Analysis – P8
## 🧾 Descripción

Proyecto de análisis exploratorio y estadístico de datos de viajes en taxi en la ciudad de Chicago (EE. UU.)
El objetivo es explorar el comportamiento de las compañías de taxi, los barrios con más viajes y probar una hipótesis sobre la duración de los trayectos bajo condiciones climáticas específicas.

## 📂 Datasets utilizados

  - /datasets/project_sql_result_01.csv

  - company_name: nombre de la empresa de taxi.

  - trips_amount: número de viajes realizados el 15 y 16 de noviembre de 2017.

  - /datasets/project_sql_result_04.csv

  - dropoff_location_name: barrio donde finalizó el viaje.

  - average_trips: promedio de viajes que finalizaron en cada barrio durante noviembre de 2017.

  - /datasets/project_sql_result_07.csv

  - start_ts: fecha y hora del inicio del viaje.

  - weather_conditions: condiciones meteorológicas.

  - duration_seconds: duración del viaje en segundos.

## 🎯 Objetivos del proyecto

  - Importar y examinar los archivos CSV.

  - Verificar y ajustar los tipos de datos.

  - Identificar los 10 barrios con mayor cantidad de finalizaciones.

  - Analizar las empresas de taxi con más viajes.

  - Crear gráficos visuales para mostrar los hallazgos.

## Probar la hipótesis:

“La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O’Hare cambia los sábados lluviosos.”

## 🧮 Estructura del análisis

  - Importación y revisión inicial

  - Lectura de archivos CSV.

  - Revisión de tipos de datos, duplicados y valores ausentes.

  - Análisis exploratorio (EDA)

  - Gráfico de empresas vs número de viajes.

  - Gráfico de los 10 barrios principales por viajes finalizados.

  - Interpretación de patrones y observaciones.

  - Prueba de hipótesis

  - Definición de hipótesis nula (H₀) y alternativa (H₁).

  - Selección de nivel de significancia α (ej. 0.05).

  - Aplicación de prueba estadística (t-test o similar).

-   Conclusión basada en el valor p.

  - Conclusiones finales

  - Resumen de los hallazgos.

  - Recomendaciones o insights basados en los datos.

## 📊 Herramientas utilizadas

  - Python 3.10+

  - Pandas, NumPy, Matplotlib, SciPy

  - Jupyter Notebook
