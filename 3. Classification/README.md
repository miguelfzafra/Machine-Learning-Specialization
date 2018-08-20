# 3. Classification

Esta carpeta contiene los apuntes y ejercicios del tercer curso de la especialización: **Classification**.
 
## Índice

| Semana | Descripción|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers) | Welcome & Linear Classifiers |
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers) | Learning Linear Classifiers |
| [Semana 3](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/3.%20Decision%20Trees) | Decision Trees |
| [Semana 4](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data) | Decision Trees Overfitting & Missing Data |


## 1. Welcome & Linear Classifiers

**Contenido**

* Fundamentos de la clasificación. Motivación con ejemplo práctico (reviews).
* Clasificador lineal. Intuición, score. Frontera de decisión (caso clasificador lineal y no lineal). Modelo (formulación). Efecto del cambio de los coeficientes en la frontera de decisión.
* Probabilidad de pertenecer a una clase. Básicos de probabilidad y propiedades (probabilidad básica, condicionada). Interpretación.
* Modelos lineales generalizados. Enlace entre score y probabilidad.
* Regresión logística (introducción). Modelo, efecto de los coeficientes.
* Inputs numéricos y categóricos. Encoding.
* Clasificación multiclase: 1 vs all.


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[1_1_Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/1_1_Intro%20Slides.pdf)|Teoría|Introducción al curso.|
|[1_2_Linear Classifiers. Logistic Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/1_2_Linear%20Classifiers.%20Logistic%20Regression%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[1_3_Linear Classifiers. Logistic Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/1_3_Linear%20Classifiers.%20Logistic%20Regression%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Linear Classifier Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/Notebooks)|Práctica|Análisis de sentimiento, interpretación, etc.|


## 2. Learning Linear Classifiers

**Contenido**

* Estimación por maximum likelihood. Intuición, motivación. Cálculo de likelihood de un conjunto de datos.
* Algoritmo para el clasificador óptimo (Gradient Ascent). Derivación formal.
* Aplicación a la regresión logística: log-likelihood, cálculo de la derivada e interpretación.
* Elección del stepsize: análisis de sensibilidad. Rule of thumb.
* Overfitting en clasificación. Efectos en el fit, en la frontera de decisión y en las probabilidades estimadas. Caso de observaciones linealmente separables.
* Regularización L1 y L2. Efectos, coefficient path, casos extremos. Cálculo del gradiente con regularización. 


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[2_1_Logistic Regression Learning Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/2_1_Logistic%20Regression%20Learning%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[2_2_Logistic Regression Overfitting Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/2_2_Logistic%20Regression%20Overfitting%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[2_3_Logistic Regression Overfitting Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/2_3_Logistic%20Regression%20Overfitting%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Linear Classifier Learning Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/Notebooks/01_Linear%20Classifier%20Learning%20Assignment.ipynb)|Práctica|Implementación gradient ascent|
|[02_Linear Classifier Regularization Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/Notebooks/02_Linear%20Classifier%20Regularization%20Assignment.ipynb)|Práctica|Regresión logística regularizada|



## 3. Decision Trees

**Contenido**

* Intuición de los árboles de decisión. Representación y obtención de la predicción al recorrerlo.
* Problema de elegir el mejor árbol. Algoritmo greedy: desarrollo, motivación, funcionamiento. Stop conditions. Decision stumps. Elección de las mejores features para hacer el split.
* Predicciones con árboles de decisión. Algoritmo de predicción.
* Clasificación multiclase. Predicción de probabilidades.
* Manejo de características numéricas (no categóricas). Threshold splits. Búsqueda del split óptimo.
* Comparación árbol de decisión vs regresión logística.

**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[3_1_Decision Trees Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/3_1_Decision%20Trees%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[3_2_Decision Trees Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/3_2_Decision%20Trees%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Decision Tree Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/Notebooks/01_Decision%20Tree%20Assignment%201.ipynb)|Práctica|Árboles de decisión: enfoque librería|
|[02_Decision Tree Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/Notebooks/02_Decision%20Tree%20Assignment%202.ipynb)|Práctica|Implementación de un árbol de decisión.|


## 4. Decision Trees Overfitting & Missing Data

**Contenido**

* Overfitting en el caso de los árboles de decisión. Efecto de la profundidad del árbol. Causa del overfitting.
* Principio de la navaja de Occam. Árboles simples frente a complejos.
* Elección de árboles simples: Early Stopping frente a Pruning. 
* Early Stopping: condiciones, retos de las mismas e incorporación al algoritmo greedy. 
* Pruning: motivación, trampas. Medida de la simpleza de los árboles. Algoritmo de pruning (lógica y modificación de la función objetivo).
* Trabajar con valores missing: diferentes estrategias. Pros y contras. Visión general.
* Aplicación de las estrategias a los árboles de decisión.


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[4_1_Decision Trees Overfitting Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/4_1_Decision%20Trees%20Overfitting%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[4_2_Decision Trees Missing Data Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/4_2_Decision%20Trees%20Missing%20Data%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[4_3_Decision Trees Overfitting & Missing Data Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/4_3_Decision%20Trees%20Overfitting%20%26%20Missing%20Data%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Decision Tree Practical Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/Notebooks/01_Decision%20Tree%20Practical%20Assignment.ipynb)|Práctica|Implementación de stopping conditions y análisis.|









