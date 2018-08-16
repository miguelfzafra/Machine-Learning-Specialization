# 2. Regression

Esta carpeta contiene los apuntes y ejercicios del segundo curso de la especialización: **Regression**.
 
## Índice

| Semana | Descripción|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/02.%20Regression/01.%20Welcome%20%26%20Simple%20Linear%20Regression) | Welcome & Simple Linear Regression |
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/02.%20Regression/02.%20Multiple%20Regression) | Multiple Regression|
| [Semana 3](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/3.%20Assessing%20Performance) | Assessing Performance|
| [Semana 4](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/4.%20Ridge%20Regression) | Ridge Regression|
| [Semana 5](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression) | Feature Selection & Lasso Regression|
| [Semana 6](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing) | NN and Kernel Regression & Closing|

## 1. Welcome & Simple Linear Regression

**Contenido**

* Explicación de los objetivos y contenidos de la especialización.
* Fundamentos de la regresión: datos, modelo, elección del mejor modelo. Regresión lineal simple (una variable dependiente y una indepentiente).
* Interpretación de los coeficientes. Elección de la mejor recta de regresión en base a métricas (RSS).
* Optimización. Métodos de obtención de la mejor recta de regresión: `gradiente = 0` o gradient descent. Comparativa de ambas alternativas.
* *High leverage points* e *Influential observations*.
* Introducción a las funciones de coste asimétricas.

**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[1_1_Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/1_1_Intro%20Slides.pdf)|Teoría|Introducción al curso.|
|[1_2_Simple Linear Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/1_2_Simple%20Linear%20Regression%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[1_3_Simple Linear Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/1_3_Simple%20Linear%20Regression%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Simple Regression PhillyCrime.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/Notebooks/01_Simple%20Regression%20PhillyCrime.ipynb)|Teoría|Puntos HLP e IO.|
|[02_Simple Regression Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/Notebooks/02_Simple%20Regression%20Assignment.ipynb)|Práctica|Cálculo explícito de parámetros, RSS, etc…|



## 2. Multiple Regression

**Contenido**

* Otros tipos de funciones: polinómicas, etc.
* Aplicación: regresión sobre series estacionales.
* Expresión general de la regresión múltiple: hiperplano de regresión.
* Interpretación de los coeficientes.
* Algoritmos para encontrar el hiperplano de regresión: closed-form solution, gradient descent. Interpretación del gradiente.

**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[2_1_Multiple Linear Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/2_1_Multiple%20Linear%20Regression%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[2_2_Multiple Linear Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/2_2_Multiple%20Linear%20Regression%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Multiple Regression Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/Notebooks/01_Multiple%20Regression%20Assignment%201.ipynb)|Práctica|Interpretación de la regresión lineal múltiple|
|[02_Numpy Tutorial.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/Notebooks/02_Numpy%20Tutorial.ipynb)|Práctica|Tutorial de numpy|
|[03_Multiple Regression Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/Notebooks/03_Multiple%20Regression%20Assignment%202.ipynb)|Práctica|Cálculo explícito del gradient descent|



## 3. Assessing Performance

**Contenido**

* Definición de la función de coste.
* Training error y generalization error (test error). Error frente a la complejidad del modelo. Training/test split.
* Fuentes del error: ruido, sesgo y varianza. Trade-off entre sesgo y varianza. Derivación formal de las fuentes de error.
* Hyperparameter tuning: enfoque train/validation/test set.


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[3_1_Assessing Performance Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/3.%20Assessing%20Performance/3_1_Assessing%20Performance%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[3_2_Assessing Performance Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/3.%20Assessing%20Performance/3_2_Assessing%20Performance%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Polynomial Regression Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/3.%20Assessing%20Performance/Notebooks/01_Polynomial%20Regression%20Assignment.ipynb)|Práctica|Test del fit a un conjunto de datos con diferentes modelos.|



## 4. Ridge Regression

**Contenido**

* Motivación de la regresión Ridge. Overfitting.
* Adición del término de regularización a la función de coste. Análisis de posibles casos. Bias-variance tradeoff en regularización. Coefficient path.
* Fit del modelo de regresión Ridge. Algoritmos: closed-form solution, gradient descent.
* Elección de lambda. K-fold Cross Validation y caso particular LOOCV.
* Problemas con el intercepto al regularizar. Soluciones: no penalizar su coeficiente, normalizar.



**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[4_1_Ridge Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/4_1_Ridge%20Regression%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[4_2_Ridge Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/4_2_Ridge%20Regression%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Overfitting Demo Ridge.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/Notebooks/01_Overfitting%20Demo%20Ridge.ipynb)|Práctica|Demostración de overfitting y Ridge.|
|[02_Ridge Regression Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/Notebooks/02_Ridge%20Regression%20Assignment%201.ipynb)|Práctica|Prueba con diferentes lambdas. Validación cruzada.|
|[03_Ridge Regression Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/Notebooks/03_Ridge%20Regression%20Assignment%202.ipynb)|Práctica|Gradient descent para regresión Ridge.|



## 5. Feature Selection & Lasso Regression

**Contenido**

* Motivación de la selección de variables.
* Maneras de realizar la selección: todas las posibles combinaciones, algoritmos *greedy*, regularización. Pros y contras.
* Motivación de la regresión Lasso: sparsity, selección implícita de características.
* Término de regularización en la función de coste. Explicación de la no idoneidad de restringir los coeficientes Ridge. Coefficient path.
* Intuición geométrica de Lasso y Ridge.
* Fit de la regresión Lasso. Algoritmos: coordinate descent (tanto para regresión no regularizada como regularizada). Normalización. Soft thresholding. Convergencia.
* Elección de lambda.
* Ventajas e inconvenientes de Lasso.


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[5_1_Lasso Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/5_1_Lasso%20Regression%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[5_2_Lasso Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/5_2_Lasso%20Regression%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Overfitting Demo Lasso.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/Notebooks/01_Overfitting%20Demo%20Lasso.ipynb)|Práctica|Demostración de overfitting y Lasso.|
|[02_Lasso Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/Notebooks/02_Lasso%20Assignment%201.ipynb)|Práctica|Prueba con diferentes lambdas. Validación cruzada.|
|[03_Lasso Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/Notebooks/03_Lasso%20Assignment%202.ipynb)|Práctica|Coordinate descent para regresión Lasso.|



## 6. NN and Kernel Regression & Closing

**Contenido**

* Introducción a la regresión no paramétrica. Fit global vs local.
* Regresión 1-NN y K-NN. Motivación. Diagramas de Voronoi. Métricas de distancia. Algoritmos. Influencia de la cantidad de datos y del ruido.
* Weighted K-NN. Kernel regression. Motivación.
* Elección de los límites lambda.
* Diferentes fits aparte de la función constante: lineal, cuadrático.
* Ventajas e inconvenientes de los métodos no paramétricos.
* Fit en el límite del número de observaciones 


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[6_1_NN and Kernel Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/6_1_NN%20and%20Kernel%20Regression%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[6_2_NN and Kernel Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/6_2_NN%20and%20Kernel%20Regression%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Local Regression.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/Notebooks/01_Local%20Regression.ipynb)|Práctica|Construcción de algoritmo KNN y predicciones.|
|[6_4_Closing Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/6_4_Closing%20Slides.pdf)|Teoría|Diapositivas de teoría.|