# 2. Regression

Esta carpeta contiene los apuntes y ejercicios del segundo curso de la especializaci�n: **Regression**.
 
## �ndice

| Semana | Descripci�n|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/02.%20Regression/01.%20Welcome%20%26%20Simple%20Linear%20Regression) | Welcome & Simple Linear Regression |
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/02.%20Regression/02.%20Multiple%20Regression) | Multiple Regression|
| [Semana 3](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/3.%20Assessing%20Performance) | Assessing Performance|
| [Semana 4](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/4.%20Ridge%20Regression) | Ridge Regression|
| [Semana 5](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression) | Feature Selection & Lasso Regression|
| [Semana 6](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing) | NN and Kernel Regression & Closing|

## 1. Welcome & Simple Linear Regression

**Contenido**

* Explicaci�n de los objetivos y contenidos de la especializaci�n.
* Fundamentos de la regresi�n: datos, modelo, elecci�n del mejor modelo. Regresi�n lineal simple (una variable dependiente y una indepentiente).
* Interpretaci�n de los coeficientes. Elecci�n de la mejor recta de regresi�n en base a m�tricas (RSS).
* Optimizaci�n. M�todos de obtenci�n de la mejor recta de regresi�n: `gradiente = 0` o gradient descent. Comparativa de ambas alternativas.
* *High leverage points* e *Influential observations*.
* Introducci�n a las funciones de coste asim�tricas.

**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[1_1_Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/1_1_Intro%20Slides.pdf)|Teor�a|Introducci�n al curso.|
|[1_2_Simple Linear Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/1_2_Simple%20Linear%20Regression%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[1_3_Simple Linear Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/1_3_Simple%20Linear%20Regression%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Simple Regression PhillyCrime.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/Notebooks/01_Simple%20Regression%20PhillyCrime.ipynb)|Teor�a|Puntos HLP e IO.|
|[02_Simple Regression Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/1.%20Welcome%20%26%20Simple%20Regression/Notebooks/02_Simple%20Regression%20Assignment.ipynb)|Pr�ctica|C�lculo expl�cito de par�metros, RSS, etc�|



## 2. Multiple Regression

**Contenido**

* Otros tipos de funciones: polin�micas, etc.
* Aplicaci�n: regresi�n sobre series estacionales.
* Expresi�n general de la regresi�n m�ltiple: hiperplano de regresi�n.
* Interpretaci�n de los coeficientes.
* Algoritmos para encontrar el hiperplano de regresi�n: closed-form solution, gradient descent. Interpretaci�n del gradiente.

**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[2_1_Multiple Linear Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/2_1_Multiple%20Linear%20Regression%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[2_2_Multiple Linear Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/2_2_Multiple%20Linear%20Regression%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Multiple Regression Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/Notebooks/01_Multiple%20Regression%20Assignment%201.ipynb)|Pr�ctica|Interpretaci�n de la regresi�n lineal m�ltiple|
|[02_Numpy Tutorial.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/Notebooks/02_Numpy%20Tutorial.ipynb)|Pr�ctica|Tutorial de numpy|
|[03_Multiple Regression Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/2.%20Multiple%20Linear%20Regression/Notebooks/03_Multiple%20Regression%20Assignment%202.ipynb)|Pr�ctica|C�lculo expl�cito del gradient descent|



## 3. Assessing Performance

**Contenido**

* Definici�n de la funci�n de coste.
* Training error y generalization error (test error). Error frente a la complejidad del modelo. Training/test split.
* Fuentes del error: ruido, sesgo y varianza. Trade-off entre sesgo y varianza. Derivaci�n formal de las fuentes de error.
* Hyperparameter tuning: enfoque train/validation/test set.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[3_1_Assessing Performance Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/3.%20Assessing%20Performance/3_1_Assessing%20Performance%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[3_2_Assessing Performance Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/3.%20Assessing%20Performance/3_2_Assessing%20Performance%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Polynomial Regression Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/3.%20Assessing%20Performance/Notebooks/01_Polynomial%20Regression%20Assignment.ipynb)|Pr�ctica|Test del fit a un conjunto de datos con diferentes modelos.|



## 4. Ridge Regression

**Contenido**

* Motivaci�n de la regresi�n Ridge. Overfitting.
* Adici�n del t�rmino de regularizaci�n a la funci�n de coste. An�lisis de posibles casos. Bias-variance tradeoff en regularizaci�n. Coefficient path.
* Fit del modelo de regresi�n Ridge. Algoritmos: closed-form solution, gradient descent.
* Elecci�n de lambda. K-fold Cross Validation y caso particular LOOCV.
* Problemas con el intercepto al regularizar. Soluciones: no penalizar su coeficiente, normalizar.



**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[4_1_Ridge Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/4_1_Ridge%20Regression%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[4_2_Ridge Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/4_2_Ridge%20Regression%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Overfitting Demo Ridge.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/Notebooks/01_Overfitting%20Demo%20Ridge.ipynb)|Pr�ctica|Demostraci�n de overfitting y Ridge.|
|[02_Ridge Regression Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/Notebooks/02_Ridge%20Regression%20Assignment%201.ipynb)|Pr�ctica|Prueba con diferentes lambdas. Validaci�n cruzada.|
|[03_Ridge Regression Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/4.%20Ridge%20Regression/Notebooks/03_Ridge%20Regression%20Assignment%202.ipynb)|Pr�ctica|Gradient descent para regresi�n Ridge.|



## 5. Feature Selection & Lasso Regression

**Contenido**

* Motivaci�n de la selecci�n de variables.
* Maneras de realizar la selecci�n: todas las posibles combinaciones, algoritmos *greedy*, regularizaci�n. Pros y contras.
* Motivaci�n de la regresi�n Lasso: sparsity, selecci�n impl�cita de caracter�sticas.
* T�rmino de regularizaci�n en la funci�n de coste. Explicaci�n de la no idoneidad de restringir los coeficientes Ridge. Coefficient path.
* Intuici�n geom�trica de Lasso y Ridge.
* Fit de la regresi�n Lasso. Algoritmos: coordinate descent (tanto para regresi�n no regularizada como regularizada). Normalizaci�n. Soft thresholding. Convergencia.
* Elecci�n de lambda.
* Ventajas e inconvenientes de Lasso.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[5_1_Lasso Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/5_1_Lasso%20Regression%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[5_2_Lasso Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/5_2_Lasso%20Regression%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Overfitting Demo Lasso.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/Notebooks/01_Overfitting%20Demo%20Lasso.ipynb)|Pr�ctica|Demostraci�n de overfitting y Lasso.|
|[02_Lasso Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/Notebooks/02_Lasso%20Assignment%201.ipynb)|Pr�ctica|Prueba con diferentes lambdas. Validaci�n cruzada.|
|[03_Lasso Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/5.%20Feature%20Selection%20%26%20Lasso%20Regression/Notebooks/03_Lasso%20Assignment%202.ipynb)|Pr�ctica|Coordinate descent para regresi�n Lasso.|



## 6. NN and Kernel Regression & Closing

**Contenido**

* Introducci�n a la regresi�n no param�trica. Fit global vs local.
* Regresi�n 1-NN y K-NN. Motivaci�n. Diagramas de Voronoi. M�tricas de distancia. Algoritmos. Influencia de la cantidad de datos y del ruido.
* Weighted K-NN. Kernel regression. Motivaci�n.
* Elecci�n de los l�mites lambda.
* Diferentes fits aparte de la funci�n constante: lineal, cuadr�tico.
* Ventajas e inconvenientes de los m�todos no param�tricos.
* Fit en el l�mite del n�mero de observaciones 


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[6_1_NN and Kernel Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/6_1_NN%20and%20Kernel%20Regression%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[6_2_NN and Kernel Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/6_2_NN%20and%20Kernel%20Regression%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Local Regression.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/Notebooks/01_Local%20Regression.ipynb)|Pr�ctica|Construcci�n de algoritmo KNN y predicciones.|
|[6_4_Closing Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/2.%20Regression/6.%20NN%20and%20Kernel%20Regression%20%26%20Closing/6_4_Closing%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|