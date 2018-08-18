# 3. Classification

Esta carpeta contiene los apuntes y ejercicios del tercer curso de la especialización: **Classification**.
 
## Índice

| Semana | Descripción|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers) | Welcome & Linear Classifiers |

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
