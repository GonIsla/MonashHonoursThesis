# Plan de tesis - Borrador

## 0. Carátula (con título de plan, nombre, legajo, dni, director/a)
### Título tentativo: Detección de puntos de cambios en series de ventas de precios y cantidades

##  1. Introducción

### 1.1 Naturaleza y alcance del problema

El problema a trabajar es la detección de puntos de cambio para series de ventas, tanto para el valor agregado de la serie como para la descomposición entre el producto de cantidades vendidas y precio medio (V = P x Q). El caso de referencia es el de un tomador de decisiones con poco conocimiento estadístico que necesita actuar sobre el negocio, por ejemplo el propietario de un pequeño comercio.

Se evaluarán los algoritmos más usados para la detección de puntos de cambios. El criterio de evaluación será la capacidad de detección de cambios de los mismos. La evaluación será en función de la magnitud de los cambios, la cantidad de datos disponibles en total en la serie y el tiempo pasado desde de el cambio. Los cambios a considerar son cambios en los valores medios de las series, cambios en la tendencia y en la estacionalidad. Es de particular interés la caracterización de la series en términos de estacionalidad y estacionariedad. En comparación a otros tipos de dominios como son la climatología y el estudio de señales,  las series de ventas presentan menor estabilidad. 
 
Dado el caso de uso de referencia, los algoritmos deben permitir caracterizar el nuevo regimen y el régimen anterior, para que sea posible comunicarlos al tomador de decisiones. Dado el dominio, el de series de ventas, se limitará la aplicación a series con un máximo de 3 años de historia y un mínimo de 3 meses. Adicionalmente, si bien los requerimientos en términos de complejidad computacional y recursos computacionales son bajos, los algoritmos deben poder ser procesados en un computador personal con 4 RAM y XX capacidad de computo en menos de XX minutos,  

  
### 1.2 Literatura pertinente

- Modelado y simulación de series temporales.
- Econométrica modelado de series de tiempo, estacionalidad e índices.

- Explicación de modelos y visualización.
- Detección de cambios. Corriente estadística de detección de puntos de cambio y de detección de anomalías. 


### 1.3 Objetivos

- O1 Caracterizar las series de ventas
	- O1.1 Identificar qué procesos estadísticos permiten modelar series de ventas y con qué rangos de parámetros.
	- O1.2 Generar series de ventas simuladas con cambios en valores medios, tendencia y estacionalidad.

- O2 Evaluar la performance de los algoritmos mas usados a partir de series
	- O2.1 Identificar los algoritmos mas utilizados
	- O2.2 Definir los criterios de comparación de los algoritmos
	- O2.3 Aplicar los algoritmos a las series generadas de objetivo 2

## 3. Metodología



Materiales: 
- Trabajo en R con paquetes de detección de cambios: ecp, changepoint, oddstream, trend, breakpoint, cpm, climtrend, prophet, forecast.
- Datos públicos: [UCI ventas de cadena británica](), [Datos públicos de facturación  de hospitales](), [Ecomerce brasilero Kaggle]().

Métodología:

## 4. Factibilidad / relevancia


## 5. Cronograma

## 6. Referencias bibliográficas 
