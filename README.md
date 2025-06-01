# ?? An��lisis Exploratorio de Datos (EDA) - Metadatos de Pel��culas de IMDb
Autor: Sebasti��n Obando Casta?o
Horas de servicio social: 5 horas + 2 horas (GitHub)
Fecha: 30 de mayo de 2025
Archivo analizado: `movie_metadata. csv`
Trabajo: Semillero AIoT TDS

# Estudio de Pel��culas de IMDb
Descripci��n de la actividad
Este proyecto lleva a cabo un an��lisis exploratorio de datos (EDA) utilizando un conjunto de datos reales obtenidos de IMDb (`movie_metadata. csv`). La meta es limpiar, describir y visualizar la informaci��n mediante Python y bibliotecas como pandas, seaborn y matplotlib.
---

Pasos realizados
# 1. Importaci��n de datos en Google Colab
- Se importa el archivo CSV utilizando pandas.
- Se revisaron las filas iniciales y el tipo de datos en cada columna.
# 2. Procesamiento de datos
- Se encontraron valores nulos en la columna `duration`.
- Se sustituyeron por la mediana de la duraci��n.
- La columna `budget` se modific�� para eliminar s��mbolos como `$` y se transform�� a formato num��rico.
- Se valid�� y se convirti�� `title_year` a un tipo num��rico para evitar problemas en los filtros.
# 3. Estad��sticas
- Se mostr�� la duraci��n media de las pel��culas.
- Se contabiliz�� cu��ntas pel��culas se estrenaron en 2008 y tienen una duraci��n entre 90 y 120 minutos.
- Se calcul�� la mediana del presupuesto de todas las pel��culas.
# 4. Gr��ficos
- Se cre�� un gr��fico de barras que ilustra la relaci��n entre la duraci��n (por rangos) y el presupuesto medio.
- Se identificaron outliers en la duraci��n usando el m��todo IQR y se elabor�� un gr��fico de barras comparando la cantidad de pel��culas normales frente a las at��picas.
---