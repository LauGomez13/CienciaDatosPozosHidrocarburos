# Curso Data Science - Ingenias - Fundación YPF + Media Chicas  
## Integrantes: 
- Laura S Gómez Velázquez 
- María Candela Herrera 
- Sofía Vaucelles  

## Objetivo del Proyecto:
El objetivo de este análisis es segmentar los pozos de hidrocarburos en grupos homogéneos utilizando modelos no supervisados para disminuir costos a través del cálculo necesario de agua. Con esta segmentación, se pretende lograr los siguientes objetivos específicos:

### Identificar Clústeres de Pozos Similares: 
Agrupar los pozos en clústeres basados en características como la profundidad, la cantidad de fracturas, el tipo de reservorio, el volumen de agua y CO2 inyectado, entre otros. Esto permitirá identificar grupos de pozos con características operativas y de rendimiento similares.

### Analizar Características de Clústeres:
Examinar y comparar las características de cada clúster para entender las diferencias y similitudes entre los grupos. Esto podría revelar patrones operacionales, geológicos o de rendimiento que podrían no ser evidentes en un análisis individual.

## Origen del Dataset: 
El dataset utilizado para este análisis es de [Datos de fractura de pozos de hidrocarburos](http://datos.energia.gob.ar/dataset/71fa2e84-0316-4a1b-af68-7f35e41f58d7/archivo/2280ad92-6ed3-403e-a095-50139863ab0d)

## Descripción del Dataset: 
El Dataset contiene información de los diferentes tipos de variables, por ejemplo, la profundidad, la cantidad de fracturas, el tipo de reservorio y el volumen del agua, entre otras. Dichas variables serán analizadas a través del anáisis exploratorio de datos.

## Desarrollo: 
Se comenzó con un Análisis Exploratorio de los datos (EDA) que nos permitió responder preguntas de diversos tipos como: ¿Cuántas filas y columnas tiene el dataset?, ¿Hay valores faltantes?, ¿Qué variables tomamos para nuestro objetivo final en común?, entre otras. Se utilizó modelo sde aprendizaje upervisado como regresión lineal, Random Forest y Gradient Boosting y modelo aprendizaje no supervisado como K-means y Análisis de Componentes PCA.
