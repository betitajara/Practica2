<div style="width: 100%; clear: both;">
<div style="float: left; width: 50%;">
<img src="http://www.uoc.edu/portal/_resources/common/imatges/marca_UOC/UOC_Masterbrand.jpg", align="left">
</div>
<div style="float: right; width: 50%;">
<p style="margin: 0; padding-top: 22px; text-align:right;">Tipología y ciclo de vida de los datos · PRAC1</p>
<p style="margin: 0; text-align:right;">2017-2 · Máster universitario en Ciencia de datos (Data science)</p>
</div>
</div>
<div style="width:100%;">&nbsp;</div>

# Práctica 2 Limpieza y validación de los datos
## Beatriz Elena Jaramillo Gallego

### Presentación

Esta práctica es parte de la asignatura Tipología y ciclo de vida de los datos, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya. En ella, se elabora un caso práctico orientado a aprender a identificar los datos relevantes para un proyecto analítico y usar las herramientas de integración, limpieza, validación y análisis de las mismas.

### Integrantes
Trabajo realizado de forma individual por Beatriz Elena Jaramillo Gallego.

### Descripción del dataset
Los datos para el análisis se ha obtenido a partir de este enlace en Kaggle Titanic: Machine Learning from Disaster (https://www.kaggle.com/c/titanic) y está constituido por 12 (variables) que presentan 891 pasajeros(filas o registros) en el archivo de train y 418 pasajeros(filas o registros) en el archivo de test.

Los datos se han dividido en dos grupos:
• Conjunto de entrenamiento (train.csv): El conjunto de entrenamiento se debe usar para construir sus
modelos de aprendizaje automático
• Conjunto de prueba (test.csv): El conjunto de prueba se debe usar para ver qué tan bien se desempeña
su modelo en datos no vistos.

__Variables__
• PassengerId: Un identificador numerico del pasajero. Es una variable númerica.
• Survived: Varibale binaria donde se indica si el pasajero sobrevivio o no. (0 = No, 1 = Yes)
• Pclass: La clase en la que viajaba el pasajero. Es una variable númerica. (1 = 1st, 2 = 2nd, 3 = 3rd)
• Name: El nombre del pasajero. Es una variable nominal.
• Sex: El sexo del pasajero. Es una varuable nominal.
• Age: La edad del pasajero. Es una variable númerica.
• SibSp: Numero de familiares cosanguineos de la persona abordo del Titanic. Es una variable númerica
• Parch: Numero de familaires de diferente grado que acompañaban a la persona abordo del Titanic. Es
una variable númerica
• Ticket: El ticket correspondiente al pasajero al momento del abordaje. Es una variable nominal.
• Fare: La tarifa del ticket segun la clase en la que abordo el pasajero. Es una variable númerica
• Cabin: El identificador de la cabina que utilizo la persona durante el viaje. Es una variable nominal
• Embarked: Indica el lugar de embarque de la persona. Es una variable nominal. (C = Cherbourg, Q =
Queenstown, S = Southampton)
