# Proyecto-Final
Integrantes: Zarina Fuentes, Laura Botero y Jhon Salazar

#PARTE DE TEORIA

*Parte 1- PROBLEMA DE REGRESION LINEAL*

* CONSULTAR LA IMPLEMENTACIÓN DEL REGRESOR LINEAL CON SKLEARN

R/= En sklearn, el modelo de regresión lineal clásica está implementado en: from sklearn.linear_model import LinearRegression
Este modelo ajusta una ecuación del tipo: <img width="326" height="45" alt="image" src="https://github.com/user-attachments/assets/76aa7adc-af0c-439f-b6e9-4ae4dcf8dc84" />
minimizando el error cuadrático medio (MSE).

- La regresión lineal en sklearn no aplica regularización.
Para regularización usa:

   -Ridge (L2)

   -Lasso (L1)

   -ElasticNet (L1 + L2)

- Es recomendable estandarizar los datos si tienen escalas muy distintas (con StandardScaler).
  *Parametros claves*
  
  fit_intercept: Si calcula o no el intercepto.

  copy_X: Si copia la matriz X o trabaja sobre ella directamente.

  n_jobs: Número de CPUs para cálculo paralelo.

*Parte 2- PROBLEMA DE CLASIFICACION LINEAL*

* CONSULTAR LA IMPLEMENTACIÓN DEL PERCEPTRÓN SIMPLE CON SKLEARN

R/= En sklearn, el percepton está implementado en la clase: from sklearn.linear_model import Perceptron. Es un algoritmo clásico de clasificación lineal que ajusta un hiperplano para separar dos clases (o más, usando estrategia one-vs-rest). 

El perceptrón en sklearn no escala automáticamente los datos; a veces conviene usar StandardScaler.

Es un algoritmo lineal: solo funciona bien si las clases son linealmente separables.

*Parametros claves*

max_iter: Número máximo de iteraciones sobre los datos

eta0: Tasa de aprendizaje

tol: Tolerancia para criterio de parada

random_state: Semilla para reproducibilidad

penalty: Tipo de regularización

alpha: Fuerza de regularización


