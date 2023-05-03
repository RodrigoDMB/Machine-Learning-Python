# Machine-Learning-Python
### Proyecto de Machine Learning con Python - Equipo 14
### Integrantes
- Del Muro Bracho,Rodrigo
- Franco Meléndez, Gerardo
- Macías Díaz, Miguel Angel
- Mayén Vázquez, Roberto Carlo
- Romero Arellano, Fernando

## Contexto general
Una cadena regional de comercio al detalle ubicada en el estado de Chihuahua quiere implementar un mecanismo para tomar mejores decisiones sobre el lugar geográfico (asentamiento o localidad) más adecuado para abrir una nueva tienda. La cadena tiene distintos formatos de tiendas como son: de conveniencia, supermercado y minisuper, además de gasolineras.


Con base en datos históricos del desempeño de las ventas de las tiendas clasificadas en sus distintos formatos, se pretende generar un modelo basado en machine learning que pueda predecir, con un cierto nivel de confianza, el comportamiento de ventas de una nueva tienda, dependiendo del asentamiento en el que se pretende abrir. De esta manera los analistas de negocio podrán tomar una mejor decisión en cuanto a la ubicación en donde una nueva tienda tendrá el mejor desempeño en ventas

## Objetivo
El objetivo de este proyecto es generar un modelo de Machine Learning que apoye la toma de decisiones sobre el lugar más adecuado para la apertura de nuevas tiendas de venta al detalle, en una región geográfica específica, haciendo una predicción del desempeño de esta nueva sucursal. El modelo hace base en un conjunto de variables geográficas y sociodemográficas de los diferentes sitios que son candidatos para la apertura. Con estas variables como entrada, se desea que el modelo pueda predecir la mejor ubicación para abrir una nueva tienda, en la que se maximice el desempeño; es decir, donde el margen de la venta neta sea mayor.

## Datasets
Para lograr el objetivo anterior se requerirán de los siguientes datasets:
1. Histórico de ventas clasificados por tienda, tipo de tienda, asentamiento o localidad y fecha.
2. Datos de demográficos clasificados por localidad o asentamiento, provenientes de la Encuesta Nacional de Ocupación y Empleo Nueva Edición (ENOEN) del INEGI
3. Datos de actividad económica clasificados por localidad provenientes de la Encuesta Nacional de Ingresos y Gastos de los Hogares 2020.

## Desarrollo
Se deberá de generar un modelo para poder determinar si algunas variables sociodemográficas y/o económicas de una localidad como son: el tamaño de la población, la actividad económica preponderante, el nivel de ingreso y gastos, tienen influencia en el comportamiento de ventas de una tienda. Para lo anterior se utilizará el dataset existente de datos históricos de las tiendas y se añadirán algunos datos provenientes de las encuestas del INEGI ya mencionadas de la localidad actual de cada tienda.

Se seleccionará el mejor método de entrenamiento y creación del modelo para generar un modelo que pueda predecir el comportamiento de ventas de una tienda, dependiendo de la localidad en la que se elija abrir la nueva tienda. 


Se tomará la decisión de abrir la nueva tienda, sólo si se supera el promedio de ventas del año pasado de las tiendas del mismo formato.


### Contenido
El repositorio contiene:
- Cuaderno Colab con proyecto final (F3M2_Proyecto_Final - Equipo 14.ipynb)
- Presentación del proyecto (Prototype Day Modelo de Apertura de Nuevas Tiendas.pptx)
- Archivo Readme.md
