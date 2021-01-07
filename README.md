# Metodología para la definición de una pólitica óptima de combustible adicional durante el planeamiento de vuelos basado en desempeño operacional

### Alexander Cipagauta / Candidato Magister Ingeniería Industrial Universidad de los Andes


### 1. Master Data: 

Creación de base de datos para algoritmos de clasificación y predicción, teniendo en cuenta información operacional y data meteorológica histórica

Debido a la cantidad de imagenes es necesario abrir el archivo por medio del siguiente link:
https://nbviewer.jupyter.org/github/AlexanderCipagauta/Tesis/blob/main/1.%20Master%20Data.ipynb


### 2. Exploration Data Analysis: 

Análisis exploratorio de datos, definición de variable de estudio y variables predictoras

https://github.com/AlexanderCipagauta/Tesis/blob/main/2.%20Master%20Exploration%20Data%20Analysis.ipynb

### 3. Classification: 

Implementación de algoritmos de clasificación, para saber si un vuelo requiere o no de combustible adicional. 
Se selecciona el mejor modelo de aprendizaje automático teniendo como métrica de desempeño, la presición (Accuracy)

https://github.com/AlexanderCipagauta/Tesis/blob/main/3.%20Master%20Algorithms%20-%20%20Classification.ipynb

### 4. Multi Classification (Prediction): 

Implementación de algoritmos de multi - clasificación para la predicción de la cantidad de combustible adicional, teniendo en cuenta que el combustible se tanquea en centenas 
Se selecciona el mejor modelo de aprendizaje automático teniendo como métrica de desempeño, la presición (Accuracy)

https://github.com/AlexanderCipagauta/Tesis/blob/main/4.%20Master%20Algorithms%20-%20%20Multi%20Classification%20(Prediction).ipynb

### 5. Policy:

Se define la pólitica de consumo de combustible adicional. Se crea la función de Python que integra los 2 modelos de clasificación y predicción, para ser usada por el equipo de despacho de la aerolinea. Así mismo se define una matriz con 1M de escenarios para ser consultado vía Excel en caso de que no se cuente con herramientas como Python

https://github.com/AlexanderCipagauta/Tesis/blob/main/5.%20Master%20Policy.ipynb
