# 3. Classification

Esta carpeta contiene los apuntes y ejercicios del tercer curso de la especializaci�n: **Classification**.
 
## �ndice

| Semana | Descripci�n|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers) | Welcome & Linear Classifiers |

## 1. Welcome & Linear Classifiers

**Contenido**

* Fundamentos de la clasificaci�n. Motivaci�n con ejemplo pr�ctico (reviews).
* Clasificador lineal. Intuici�n, score. Frontera de decisi�n (caso clasificador lineal y no lineal). Modelo (formulaci�n). Efecto del cambio de los coeficientes en la frontera de decisi�n.
* Probabilidad de pertenecer a una clase. B�sicos de probabilidad y propiedades (probabilidad b�sica, condicionada). Interpretaci�n.
* Modelos lineales generalizados. Enlace entre score y probabilidad.
* Regresi�n log�stica (introducci�n). Modelo, efecto de los coeficientes.
* Inputs num�ricos y categ�ricos. Encoding.
* Clasificaci�n multiclase: 1 vs all.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[1_1_Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/1_1_Intro%20Slides.pdf)|Teor�a|Introducci�n al curso.|
|[1_2_Linear Classifiers. Logistic Regression Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/1_2_Linear%20Classifiers.%20Logistic%20Regression%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[1_3_Linear Classifiers. Logistic Regression Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/1_3_Linear%20Classifiers.%20Logistic%20Regression%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Linear Classifier Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers/Notebooks)|Pr�ctica|An�lisis de sentimiento, interpretaci�n, etc.|


## 2. Learning Linear Classifiers

**Contenido**

* Estimaci�n por maximum likelihood. Intuici�n, motivaci�n. C�lculo de likelihood de un conjunto de datos.
* Algoritmo para el clasificador �ptimo (Gradient Ascent). Derivaci�n formal.
* Aplicaci�n a la regresi�n log�stica: log-likelihood, c�lculo de la derivada e interpretaci�n.
* Elecci�n del stepsize: an�lisis de sensibilidad. Rule of thumb.
* Overfitting en clasificaci�n. Efectos en el fit, en la frontera de decisi�n y en las probabilidades estimadas. Caso de observaciones linealmente separables.
* Regularizaci�n L1 y L2. Efectos, coefficient path, casos extremos. C�lculo del gradiente con regularizaci�n. 


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[2_1_Logistic Regression Learning Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/2_1_Logistic%20Regression%20Learning%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[2_2_Logistic Regression Overfitting Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/2_2_Logistic%20Regression%20Overfitting%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[2_3_Logistic Regression Overfitting Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/2_3_Logistic%20Regression%20Overfitting%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Linear Classifier Learning Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/Notebooks/01_Linear%20Classifier%20Learning%20Assignment.ipynb)|Pr�ctica|Implementaci�n gradient ascent|
|[02_Linear Classifier Regularization Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers/Notebooks/02_Linear%20Classifier%20Regularization%20Assignment.ipynb)|Pr�ctica|Regresi�n log�stica regularizada|
