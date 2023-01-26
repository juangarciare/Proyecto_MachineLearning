Garci Ressia Juan Ignacio
En este README esta la informacion mas importantes de mis dos modelos de prediccion utilizados en el repositorio donde estamos.

En el archivo modelo_no_supervisado.ipynb encotraran como relice paso a paso mi modelo de prediccion no supervisado usando K_means- 
En el archivo modelo_supervisado.ipynb encotraran como relice paso a paso mi modelo de prediccion supervisado usando arbol de clasificacion- 
README - Información sobre el proyecto

El objetivo de estos notbooks es realizar dos modelos de prediccion, con el fin de crear categorias basadas en los precios de las propiedades, sobre una base de datos que posee informacion sobre propiedades publicadas.
 
Para la realizacion de mis predicciones use los archivos situados en el repositorio, llamados 'test.parquet' y 'train.parquet'.

En el modelo Supervisado el objetivo fue predecir el valor de las propiedades en dos tipos de clasificacion:
Por debajo del precio de $999, representado con el valor 1
Por encima del precio de $999,  representado con el valor 0

En el modelo no supervisado los tipos de clasificacion para dividir el precio de las propiedades fueron tres:
bajo (igual o por debajo de $999), representado con el valor 0
medio(para precios entre $1000 y $1999), representados con el valor 1
alto(para precios desde 2000 dólares en adelante), representados con el valor 1

Ambos notebooks contienen  el analisis exploratorio de los datos, la transformacion de los mismos y el modelo que fue utilizado. 

Muchas Gracias!!


