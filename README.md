# Proyecto N°2 - Data Analyst
![Texto alternativo](https://2.bp.blogspot.com/_K-TXLQR7DhQ/TD_Zo3BFBjI/AAAAAAAACsI/TvFGPEGiUSU/s1600/planecrash700.jpg)


## Rol a desarrollar

La Organización de Aviación Civil Internacional (OACI) quiere analizar accidentes aéreos desde principios del siglo XX. El objetivo es realizar un análisis de datos de todo tipo haciendote preguntas metiendote en el rol de un empleado y asi poder llegar a conclusiones y luego crear un dashboard informativo para poder explicar todo lo que fuiste haciendo.


## ETL(Extract, Transform, Load)

En el ETL lo primero que hice fue cragar las librerias que ibas a usar y luego leer el archivo csv de accidnetes aereos en Visual Code para ver que datos tenia que cambiar, acomodar, ordenar y eliminar. Cambie de nombre los nombres de las columnas para que queden todas en el mismo idioma y sentido. Despues tuve que elimnar datos duplicados, outliers, nulos.

## EDA(Análisis Exploratorio de Datos)

En el EDA comence priemero viendo la relacion de las columnas entre ellas con una matriz de correlacion, luego hice un mapa de calor de los valores nulos y con eso elimine tres columnas que tenian muchos valores faltantes y cuando ya tenia todo ordenado y acomodado comence a hacerme preguntas de que es lo que quiero y que graficos son los mejores para poder resumir el csv y que alguien que lo mire lo pueda entender, y no nesesite tener conocimientos para entener los graficos. 
El objetivo mio era poder hacer vamrios graficos de cada tema y algunos con mas detalles para poder llegar a conclusiones y luego poder hacer las KPI.

## KPI's

# 1) Evaluar la disminución de un 10% la tasa de fatalidad de la tripulación en los últimos 10 años, comparado a la década anterior.
En este KPI lo que hice fue primero calcule las taasas de fatalidad del 2001 al 2011 y la del 2011 al 2021 y cuando ya sabia cuales eran lois datos en esas dos decadas lo que hice fue calcular la diferencia porcentual a lo que llegue a un 13% aproximado, por ende no cumple el objetivo de la KPI que era la disminucion de un 10%
# 2) Reducir un 10% la cantidad de accidentes en Rusia
En este KPI luego de lo graficos del EDA vi que los paises con mayor cantidad de accidentes eran Estados Unidos y Rusia por lo que me fui por el pais Rusia porque me interesaba mas el pai, entonces hic eun grafico filtrando los accidentes de todos los años del pais Rusia y pude ver que apartir del año 1994 que es uno de los años con mas accidentes, de ahi hasta 2021 la cantidad de accidentes empieza a bajar hasta un accidente por año, por eso este KPI se cumplio aunque en el 2001 y 2010 hubo un aumento de accidentes los demas años fueron bajos comparados a los demas.
# 3) Aumentar como minimo un 10% de los sobrevivientes de la decada del 2011 al 2021 que la del 2001 al 2011
En este KPI lo que hice fue calcular la tasa de supervivencia del 2001 al 2011 y la tasa de supervivencia del 2011 al 2021 y lo que queria era que en la decada actual del 2011 al 2021 esa tasa de supervivencia aumente mas que la anterior decada entonces eso querria decir que o los aviones son mas seguros o hay menos accidentes pero cuando hice el analisis de cada uno me dio que lla tasa de supervivencia paso de 30% a 27%, eso significa que disminuyo entonces hay menos sobrevivientes y mas muertes por ende no se cumple el objetivo de la KPI solicitada.

## Dashboard
En el Dashboard trate de incormporar la mayor informacion que tenia en el Visual Code, mucho que no pero los mas importante para que cualquier persona que mire primero el dashboard pueda ver de que estamos hablando, el analisis de los accidentes aereos que suceden en el mundo y los KPI que se realizaron. 

## Analisis personal
A medida que iba avanzando en este proyecto iba entendiendo siempre un poquito mas, pero cuando estaba terminando el EDA y arranacando el primer KPI me hice una pregunta sobre este tema;
¿Cuando es mas seguro viajar en avion entre los años de 1908 y 2021?
Y esta pregunta la iba a dejar pasar pero no se me iba de la cabeza por ende comence a hacer el analisis, divide todos los años en decadas, luego en cada rango calcule la cantidad de accidentes, el porcentaje de muertes con sus respectivas cantidades de cada decada y llegue ala conclusion de que es mas seguro viajar estos ultimos 10 años, del 2011 al 2021 ya que fue la decada de menor muertes y menor accidentes, sacando la primer decada que seguro era porque no habia tantos aviones.

