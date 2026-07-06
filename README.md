# An-lisis-del-Mercado-Gastron-mico---Denver
Este documento resume los hallazgos y el proceso técnico realizado para el análisis de  viabilidad de restaurantes vegetarianos en Denver, Colorado. 
Análisis del Mercado Gastronómico - 
Denver 
Avance del Proyecto Integrador (PIM1) 
Conde E. Camila 
0 

1. Documentación del Proceso (README) 
Este documento resume los hallazgos y el proceso técnico realizado para el análisis de 
viabilidad de restaurantes vegetarianos en Denver, Colorado.

1.1 Introducción y Objetivo 
El objetivo principal es identificar el perfil del consumidor local y contrastarlo con la 
oferta actual extraída de fuentes externas (Yelp), permitiendo una toma de decisiones 
basada en datos para nuevos emprendimientos gastronómicos. 

1.2 Procesamiento y Limpieza de Datos (EDA) 
Tratamiento de Outliers: Se identificó un error en la columna de edad (valores de 300 
años), los cuales fueron normalizados a 30 años para evitar sesgos estadísticos en los 
análisis de correlación y consumo de alcohol. 
Filtrado Geográfico: Se segmentó la base de datos para priorizar residentes de 
Denver, asegurando la relevancia local del estudio. 

1.3 Insights Clave del Negocio 
●  Relación Ingreso-Gasto: Existe una correlación positiva que valida el alto poder 
adquisitivo de la zona. 
●  Perfil Premium: El 25% de los clientes con mayor gasto prefiere opciones 
saludables/vegetarianas. 
●  Consumo de Alcohol: El consumo se estabiliza en el rango de 30-50 años, 
definiendo el target para promociones. 

1.4 Integración API Yelp 
Se integraron datos de 50 establecimientos en Denver. La oferta actual goza de una 
reputación alta (4.0+ estrellas), lo que indica un mercado competitivo que exige 
estándares elevados de calidad. 
1 

3. Guía de Interpretación para Notebooks 
Estos párrafos deben insertarse en celdas Markdown debajo de sus respectivos gráficos 
para cumplir con los criterios de evaluación.

2.1 Para Avance_EDA_Conde.ipynb 
Distribución por Ciudad:  
“Este gráfico permite dimensionar el alcance geográfico de nuestra muestra. Identificar 
que la mayor concentración de usuarios reside en ciudades como Denver justifica el 
enfoque del proyecto, asegurando que las conclusiones tengan representatividad 
estadística local.” 

Relación Ingresos vs Gasto:  
“Se observa una correlación positiva moderada: a medida que aumentan los ingresos, el 
presupuesto destinado a alimentación tiende a crecer. Esto sugiere que el mercado de 
Denver es receptivo a ofertas de mayor valor.” 

Consumo de Alcohol y Edad:  
“Tras corregir los valores atípicos de edad, el análisis muestra que el consumo de licor 
es consistente en el rango de 30 a 50 años. Esta información es vital para el diseño de 
la carta de bebidas y estrategias de Happy Hour.” 

2.2 Para Avance_API_Yelp_Conde.ipynb 
Análisis de Reputación:  
“La integración de datos de la API de Yelp revela que la oferta vegetariana en Denver 
tiene una alta reputación. Existe una oportunidad para nuevos establecimientos si 
logran incentivar la retroalimentación de los clientes.”
