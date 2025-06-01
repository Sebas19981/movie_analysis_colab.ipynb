# Analisis Exploratorio de Datos (EDA) - Metadatos de Peliculas de IMDb
Autor: Sebastian Obando Castaño
Horas de servicio social: 5 horas + 2 horas (GitHub)
Fecha: 30 de mayo de 2025
Archivo analizado: `movie_metadata. csv`
Trabajo: Semillero AIoT TDS

# Estudio de Peliculas de IMDb
Descripcion de la actividad
Este proyecto lleva a cabo un an¨¢lisis exploratorio de datos (EDA) utilizando un conjunto de datos reales obtenidos de IMDb (`movie_metadata. csv`). La meta es limpiar, describir y visualizar la informaci¨®n mediante Python y bibliotecas como pandas, seaborn y matplotlib.
---

Pasos realizados
# 1. Importacion de datos en Google Colab
- Se importa el archivo CSV utilizando pandas.
- Se revisaron las filas iniciales y el tipo de datos en cada columna.
# 2. Procesamiento de datos
- Se encontraron valores nulos en la columna `duration`.
- Se sustituyeron por la mediana de la duracion.
- La columna `budget` se modifica para eliminar simbolos como `$` y se transforma a formato numerico.
- Se valida y se convirtiron `title_year` a un tipo numerico para evitar problemas en los filtros.
# 3. Estadasticas
- Se mostr¨® la duracion media de las peliculas.
- Se contabiliza cuantas peliculas se estrenaron en 2008 y tienen una duracion entre 90 y 120 minutos.
- Se calculo la mediana del presupuesto de todas las pel¨ªculas.
# 4. Gr¨¢ficos
- Se cre¨® un gr¨¢fico de barras que ilustra la relaci¨®n entre la duraci¨®n (por rangos) y el presupuesto medio.
- Se identificaron outliers en la duraci¨®n usando el m¨¦todo IQR y se elabor¨® un gr¨¢fico de barras comparando la cantidad de pel¨ªculas normales frente a las at¨ªpicas.
---
