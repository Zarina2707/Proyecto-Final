# Proyecto-Final
Integrantes: Zarina Fuentes, Laura Botero y Jhon Salazar

*Parte 1- PROBLEMA DE REGRESION LINEAL*

CONSULTAR LA IMPLEMENTACIÓN DEL REGRESOR LINEAL CON SKLEARN

R/=

*Parte 2- PROBLEMA DE CLASIFICACION LINEAL*

CONSULTAR LA IMPLEMENTACIÓN DEL PERCEPTRÓN SIMPLE CON SKLEARN

R/= En sklearn, el percepton está implementado en la clase: from sklearn.linear_model import Perceptron. Es un algoritmo clásico de clasificación lineal que ajusta un hiperplano para separar dos clases (o más, usando estrategia one-vs-rest). 

El perceptrón en sklearn no escala automáticamente los datos; a veces conviene usar StandardScaler.

Es un algoritmo lineal: solo funciona bien si las clases son linealmente separables.

*Parametros*

max_iter: Número máximo de iteraciones sobre los datos

eta0: Tasa de aprendizaje

tol: Tolerancia para criterio de parada

random_state: Semilla para reproducibilidad

penalty: Tipo de regularización

alpha: Fuerza de regularización


