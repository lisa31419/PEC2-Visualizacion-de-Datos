# Incendios Forestales en Canadá 

## Descripción

Este repositorio sirve como contenedor de la PEC2 de la asignatura Visualización de Datos del Máster de Ciencia de Datos de la UOC (2023). Para realizar esta práctica se han asignado las técnicas del histograma, Diagrama de Voronoy y Diagrama de Ridgeline para su estudio. Por ende, su visualización se centrará en el dataset seleccionado de Kaggle [Capstone Wildfires in Canada](https://www.kaggle.com/code/accastano/capstone-wildfires-in-canada/input), que nos proporciona información sobre incendios forestales en Canadá de 1950 a 2021.

## Estructura del Conjunto de Datos
El conjutno de datos contiene una gran diversidad de variables. Sin embargo, nos centraremos en una selección de ellas, donde el primer valor será el nombre asignado en la entrega y el segundo, el nombre original:

- **Fire_ID** (FID): ID numérico único para cada indendio registrado.
- **Provincia** (SRC_AGENCY): Provincia de Canadá en la que se ha reportado el incendio y que está ligada a una agencia reportadora.
- **Latitud** (LATITUDE)
- **Longitud** (LONGITUDE)
- **Fecha** (REP_DATE): Fecha en que se registró el incendio.
- **Hectareas** (SIZE_HA): Número de hectáreas afectadas por el incendio.
- **Zona** (ECOZ_NAME): Nombre de la zona o ecosistema afectado por el incendio.

Dentro del conjunto de datos también se crearán las siguientes variables:
- **Mes:** Nombre del mes en que ocurrió el incendio, extraída de Fecha y convertida a texto.


## Uso del Notebook de R Studio

El notebook de R Studio utiliza este conjunto de datos para realizar análisis y visualizaciones de los incendios forestales en Canadá. Aquí se presentan tres gráficas principales:

1. **Histogramas:**
   - Técnica de visualización empleada para estudiar la frecuencia de longitudes afectadas en los incendios del 2000 en Canadá.
     ![image](https://github.com/lisa31419/PEC2-Visualizacion-de-Datos/assets/57969201/aac292ef-7ee7-4fdb-aad9-c38668067531)


2. **Diagrama de Voronoi:**
   - Técnica de visualización empleada para estudiar espacialmente de la distribución de los incendios forestales del 2000 en la provincia del Yukon.
     ![image](https://github.com/lisa31419/PEC2-Visualizacion-de-Datos/assets/57969201/1188b9c2-75f3-4ada-b35b-46d8b348b9d4)

    
3. **Ridgeline Chart:**
   -  Técnica de visualización empleada para estudiar la distribución de las hectáreas quemadas en el Top %0 mayores incendios de Canadá a lo largo de diferentes meses, proporcionando una perspectiva única de la variabilidad estacional.
     ![image](https://github.com/lisa31419/PEC2-Visualizacion-de-Datos/assets/57969201/fb3610d9-7645-4abf-8ffd-ac94e63f0177)


## Instrucciones para Ejecutar el Notebook

1. Descarga el conjunto de datos de [incendios forestales de Canadá](https://www.kaggle.com/code/accastano/capstone-wildfires-in-canada/input).
2. Abre el notebook en R Studio.
3. Ejecuta las celdas de código para cargar y analizar el conjunto de datos.
4. Explora las visualizaciones generadas para comprender mejor la distribución y características de los incendios forestales.

¡Espero que estas visualizaciones proporcionen una comprensión más profunda de la magnitud y la distribución de los incendios forestales en Canadá!
