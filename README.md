# Proyecto 1 - Shark Attacks 

El objetivo de este proyecto es limpiar, transformar y analizar un dataset que recoge los ataques de tiburones a nivel global usando las librerías Pandas, Numpy, Matplotlib y Seaborn. El dataset usado se encuentra en el siguiente link: [Shark attacks](https://www.kaggle.com/datasets/teajay/global-shark-attacks)

## Hipótesis
La idea del proyecto es dar una serie de recomendaciones para evitar sufrir un ataque letal de tiburón si vas de vacaciones a alguno de los países con mayor tasa de ataques. Las hipótesis de las que he partido para analizar estos datos y extraer conclusiones son: 
- Hipótesis 1: ¿En qué países hay un porcentaje más elevado de muertes por ataques de tiburón?
- Hipótesis 2: ¿En que estación del año hay más riesgo de morir por un ataque de tiburón en estos países?
- Hipótesis 3: ¿Cuáles son las actividades con las que se producen más muertes?
- Hipótesis 4: ¿En estos países mueren más mujeres o hombres?

## Procedimiento
El data cleaning está estructurado en una limpieza general donde me quedo con las columnas que me interesan para mi análisis y una limpieza específica de cada una estas. Del archivo ```attacks.csv``` las columnas relevantes para mi análisis son case_number, date, fatal, country y activity. Por otro lado, he usado otro data set llamado ```countries_lat_lon.csv``` que contiene las latitudes de cada país, de esta forma he podido determinar en que estación del año se produjo el ataque.  En el archivo ```cleaning.ipynb``` encontrareis el proceso que he seguido más detallado y explicado y el resultado de este cleaning es el archivo ```attacks-limpio.csv```

En el archivo ```analysis.ipynb```  he realizado el análisis del data set limpio en base a mis hipótesis planteadas  mediante gráficos. 

## Conclusiones
1.	Los dos países con un mayor número de ataques con diferencia son Australia y USA. En USA se producen muchos más ataques de tiburones, sin embargo, el porcentaje de muertes por ataques de tiburón es mucho más elevado en Australia. 
2.	En ambos países la estación del año con más muertes es verano y la que menos invierno. Sin embargo, la segunda época más peligrosa en USA es otoño, mientras que en Australia no hay demasiada diferencia entre otoño e invierno.
3.	Tanto en Australia como en USA, nadar, hacer submarinismo, surfear o pescar son las actividades con las que más personas mueren atacadas por un tiburón. Sin embargo, hay diferencias entre los países, por ejemplo, la pesca provoca muchas más muertes en USA que en Australia. 
4.	En ambos países mueren más hombres que mujeres, no hay ninguna diferencia por país. 


![](memeshark.jpg)

