# Trabajo-Final-Ing-2025

**Calidad de Aire**
**Introducción**

En este trabajo vamos a analizar y predecir la calidad del aire, ya que se ha incrementado la preocupación por la contaminación atmosférica y sus impactos en la salud pública y el medio ambiente. La alta exposición a contaminantes como el material particulado, está asociada a enfermedades respiratorias, cardiovasculares, entre otras. 
La cobertura de estaciones de monitoreo de calidad del aire es limitada en muchas áreas, lo que dificulta la toma de decisiones informadas y la implementación de políticas públicas efectivas.

**Objetivo**
Crear un modelo predictivo para identificar las zonas con mayor contaminación atmosférica. Utilizaremos los datos de la OMS (Organización Mundual de la Salud) sobre la calidad del aire ambiente.Dicha organización recopila las mediciones terrestres de las concentraciones medias anuales de dióxido de nitrógeno (NO 2), material particulado de un diámetro igual o menor a 10 μm (PM 10 ) o igual o menor a 2,5 μm (PM 2,5 ), que tienen como objetivo representar un promedio para la ciudad o pueblo en su conjunto, en lugar de para estaciones individuales. Ambos grupos de contaminantes se originan principalmente de actividades humanas relacionadas con la combustión de combustibles fósiles. 

**Integrantes**

-Anne Kathrin, Huber

-Maria Florencia, Siarri

**Website del database**

(https://www.who.int/data/gho/data/themes/air-pollution/who-air-quality-database)

La base de datos incluye concentraciones medias anuales de PM10 PM 2,5 y NO2. Basadas en mediciones terrestres de estos contaminantes. Proporciona un promedio para una ciudad o pueblo en su conjunto, en lugar de estaciones indiciduales . La mayoria de las mediociones se realizaron entre 2010 y 2019.

**Estructura del Repositorio**

README.md
acondicionamiento.ipynb - archivo donde se realiza el renombre de columnas y limpieza general de los bloques temáticos
analisis_exploratorio.ipynb
ModelosClasificacion.ipynb - Regresión Logística, Random Forest y Support Vector Machine, para clasificar individuos con/sin hipertensión
AprendizajeNoSupervisado.ipynb - Reducción de dimensionalidad(análisis de componentes principales y análisis factorial de datos mixtos) y Clustering (Kmeans y DBSCAN)
datasets - carpeta con los archivos que se utilizan y exportan en cada notebook del repositorio
| friesgo_2018_raw.txt - archivo original
| friesgo_2018.csv
| friesgo_analisis.csv
| friesgo.csv
utils - carpeta con archivos de utilidad
| codificaciones.py - diccionarios correspondientes a toda la codificacion usada en los datasets
| funciones.py - funciones creadas para el uso comun en todo el analisis













Fuente de datos:

Las principales fuentes de datos fueron:
Informes oficiales de paises enviados a la OMS a solicitud informes y citios web nacionales y subnacionales. Contiene mediciones de PM 2,5 o PM 10.
Mediciones terrestres recopiladas en el marco del proyecto Global Burden of Disease. Para NO2 se obtuvieron mediciones terrestres recopiladas por la investigación de Larkin Et al. en 2017
También se utilizaron mediciones reportadas por las siguientes redes regionales:
Clean air for Asia, la base de datos de informes electronicos de calidad de aire de la agencia europea de mediambiente y el programa Air NOW y las embajadas y consulado delos EEUU.
Sino se disponia de datos oficiales, se utilizaron valores de revistas revisadas por pares 

 Metodología:
 

