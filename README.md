# Análisis Predictivo para una Tienda Minorista 🤖📊
Este proyecto fue desarrollado como parte de un curso de Data Science y Machine Learning, con el objetivo de predecir las ventas del próximo mes en una tienda minorista. Para lograrlo, se utilizó Python junto con las librerías Pandas, Matplotlib, Seaborn y Scikit-learn.

<h2>Proceso:</h2>
1. Preparacion de los datos: 

* Se transformó un archivo CSV en un DataFrame utilizando Pandas.
  
* Analicé el contenido del DataFrame, que incluía información como las fechas de las ventas, si la venta se realizó en un día festivo o bajo promoción, el monto de la venta y el día de la semana.
  
* Verifiqué que no hubiera datos faltantes ni registros duplicados. Sin embargo, detecté que el formato de las fechas era incorrecto, por lo que realicé la conversión necesaria antes de continuar.
  
2. Analisis exploratorio de datos (EDA):

* Exploré los datos a fondo para comprender mejor el comportamiento de las ventas.

* Realicé visualizaciones sobre: La distribución de las ventas, la relación entre ventas y día de la semana calculando el promedio de ventas, comparaciones entre ventas con y sin promociones, comparaciones entre días normales y festivos, la interacción entre promociones y días festivos en las ventas.
  
3. Seleciono el modelo: En este caso tengo tres opciones de modelos para predecir las futuras ventas, Modelo Lineal, Árbol de decisión o Random Forest. Procedo a entrenar cada modelo y obtener su puntaje para saber cuál es el mas confiable, por lo que el modelo lineal fue el elegido.

4. Entrenamiento y evaluación del modelo: Una vez elegido el modelo, lo entreno y realizo las predicciones, visualizo los resultados mediante dos gráficos que son las Ventas Reales vs Ventas Predichas y la comparación de las Ventas Reales vs Ventas Predichas a lo largo del tiempo.

5. Conclusión: A partir de los gráficos obtemidos, realicé una breve conlusión y proporcioné recomendaciones a la tienda minorista para poder mejorar sus ventas a futuro.
