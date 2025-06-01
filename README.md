# ?? An芍lisis Exploratorio de Datos (EDA) - Metadatos de Pel赤culas de IMDb
Autor: Sebasti芍n Obando Casta?o
Horas de servicio social: 5 horas + 2 horas (GitHub)
Fecha: 30 de mayo de 2025
Archivo analizado: `movie_metadata. csv`
Trabajo: Semillero AIoT TDS

# Estudio de Pel赤culas de IMDb
Descripci車n de la actividad
Este proyecto lleva a cabo un an芍lisis exploratorio de datos (EDA) utilizando un conjunto de datos reales obtenidos de IMDb (`movie_metadata. csv`). La meta es limpiar, describir y visualizar la informaci車n mediante Python y bibliotecas como pandas, seaborn y matplotlib.
---

Pasos realizados
# 1. Importaci車n de datos en Google Colab
- Se importa el archivo CSV utilizando pandas.
- Se revisaron las filas iniciales y el tipo de datos en cada columna.
# 2. Procesamiento de datos
- Se encontraron valores nulos en la columna `duration`.
- Se sustituyeron por la mediana de la duraci車n.
- La columna `budget` se modific車 para eliminar s赤mbolos como `$` y se transform車 a formato num谷rico.
- Se valid車 y se convirti車 `title_year` a un tipo num谷rico para evitar problemas en los filtros.
# 3. Estad赤sticas
- Se mostr車 la duraci車n media de las pel赤culas.
- Se contabiliz車 cu芍ntas pel赤culas se estrenaron en 2008 y tienen una duraci車n entre 90 y 120 minutos.
- Se calcul車 la mediana del presupuesto de todas las pel赤culas.
# 4. Gr芍ficos
- Se cre車 un gr芍fico de barras que ilustra la relaci車n entre la duraci車n (por rangos) y el presupuesto medio.
- Se identificaron outliers en la duraci車n usando el m谷todo IQR y se elabor車 un gr芍fico de barras comparando la cantidad de pel赤culas normales frente a las at赤picas.
---