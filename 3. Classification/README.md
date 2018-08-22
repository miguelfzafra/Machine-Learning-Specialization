# 3. Classification

Esta carpeta contiene los apuntes y ejercicios del tercer curso de la especializaci�n: **Classification**.
 
## �ndice

| Semana | Descripci�n|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/1.%20Welcome%20%26%20Linear%20Classifiers) | Welcome & Linear Classifiers |
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/2.%20Learning%20Linear%20Classifiers) | Learning Linear Classifiers |
| [Semana 3](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/3.%20Decision%20Trees) | Decision Trees |
| [Semana 4](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data) | Decision Trees Overfitting & Missing Data |
| [Semana 5](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/5.%20Boosting) | Boosting|
| [Semana 6](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/6.%20Precision%20-%20Recall) | Precision - Recall |
| [Semana 7](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/3.%20Classification/7.%20Scaling%20%26%20Online%20Learning) | Scaling to Huge Datasets & Online Learning|


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



## 3. Decision Trees

**Contenido**

* Intuici�n de los �rboles de decisi�n. Representaci�n y obtenci�n de la predicci�n al recorrerlo.
* Problema de elegir el mejor �rbol. Algoritmo greedy: desarrollo, motivaci�n, funcionamiento. Stop conditions. Decision stumps. Elecci�n de las mejores features para hacer el split.
* Predicciones con �rboles de decisi�n. Algoritmo de predicci�n.
* Clasificaci�n multiclase. Predicci�n de probabilidades.
* Manejo de caracter�sticas num�ricas (no categ�ricas). Threshold splits. B�squeda del split �ptimo.
* Comparaci�n �rbol de decisi�n vs regresi�n log�stica.

**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[3_1_Decision Trees Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/3_1_Decision%20Trees%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[3_2_Decision Trees Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/3_2_Decision%20Trees%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Decision Tree Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/Notebooks/01_Decision%20Tree%20Assignment%201.ipynb)|Pr�ctica|�rboles de decisi�n: enfoque librer�a|
|[02_Decision Tree Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/3.%20Decision%20Trees/Notebooks/02_Decision%20Tree%20Assignment%202.ipynb)|Pr�ctica|Implementaci�n de un �rbol de decisi�n.|


## 4. Decision Trees Overfitting & Missing Data

**Contenido**

* Overfitting en el caso de los �rboles de decisi�n. Efecto de la profundidad del �rbol. Causa del overfitting.
* Principio de la navaja de Occam. �rboles simples frente a complejos.
* Elecci�n de �rboles simples: Early Stopping frente a Pruning. 
* Early Stopping: condiciones, retos de las mismas e incorporaci�n al algoritmo greedy. 
* Pruning: motivaci�n, trampas. Medida de la simpleza de los �rboles. Algoritmo de pruning (l�gica y modificaci�n de la funci�n objetivo).
* Trabajar con valores missing: diferentes estrategias. Pros y contras. Visi�n general.
* Aplicaci�n de las estrategias a los �rboles de decisi�n.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[4_1_Decision Trees Overfitting Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/4_1_Decision%20Trees%20Overfitting%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[4_2_Decision Trees Missing Data Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/4_2_Decision%20Trees%20Missing%20Data%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[4_3_Decision Trees Overfitting & Missing Data Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/4_3_Decision%20Trees%20Overfitting%20%26%20Missing%20Data%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Decision Tree Practical Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/4.%20Decision%20Trees%20Overfitting%20%26%20Missing%20Data/Notebooks/01_Decision%20Tree%20Practical%20Assignment.ipynb)|Pr�ctica|Implementaci�n de stopping conditions y an�lisis.|



## 5. Boosting

**Contenido**

* Introducci�n al boosting. Antecedentes y motivaci�n.
* Ensemble classifiers. Funcionamiento general. Caso particular de ensemble classifier con decision stumps.
* Boosting. Weighted data. Explicaci�n del algoritmo.
* AdaBoost. C�lculo del peso de cada modelo (mediante Weighted Classification Error) y de los pesos de los puntos (mediante la f�rmula para actualizar los pesos y el normalizado). Ejemplo de aplicaci�n.
* Convergencia de los algoritmos de boosting.
* Overfitting en el boosting. Elecci�n del n�mero de iteraciones (hiperpar�metro).
* Impacto del boosting y variantes.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[5_1_Boosting Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/5.%20Boosting/5_1_Boosting%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[5_2_Boosted Trees Advanced Material.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/5.%20Boosting/5_2_Boosted%20Trees%20Advanced%20Material.pdf)|Teor�a|Diapositivas de teor�a avanzada.|
|[5_3_Boosting Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/5.%20Boosting/5_3_Boosting%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Boosting Assignment 1.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/5.%20Boosting/Notebooks/01_Boosting%20Assignment%201.ipynb)|Pr�ctica|Boosting: enfoque librer�a|
|[02_Boosting Assignment 2.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/5.%20Boosting/Notebooks/02_Boosting%20Assignment%202.ipynb)|Pr�ctica|Implementaci�n de boosting.|



## 6. Precision - Recall

**Contenido**

* Motivaci�n de otras medidas adem�s de la accuracy. Ejemplo pr�ctico.
* Noci�n de "buen clasificador".
* Precision y Recall: explicaci�n, c�lculo e intuici�n.
* Tipos de errores. Matriz de confusi�n. TP, TN, FP, FN.
* Modelos en funci�n de precision-recall. Trade-off. Utilizaci�n de probabilidades para fijar un l�mite.
* Curva precision-recall.
* Comparaci�n de algoritmos: otras medidas.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[6_1_Precision - Recall Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/6.%20Precision%20-%20Recall/6_1_Precision%20-%20Recall%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[6_2_Precision - Recall Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/6.%20Precision%20-%20Recall/6_2_Precision%20-%20Recall%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Precision Recall Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/6.%20Precision%20-%20Recall/Notebooks/01_Precision%20Recall%20Assignment.ipynb)|Pr�ctica|Pr�ctica Precision Recall|


## 7. Scaling to Huge Datasets & Online Learning

**Contenido**

* Historia del Machine Learning. Situaci�n actual. Volumen de datos.
* Algoritmo de gradient ascent para datos enormes. Escalabilidad.
* Introducci�n al Stochastic Gradient Ascent. Motivaci�n e intuici�n. Comparaci�n en t�rminos computacionales. Funcionamiento.
* Convergence paths.
* Trucos pr�cticos: shuffle data, elecci�n del step-size, elecci�n de los pesos estimados.
* Stochastic gradient con mini-batches.
* Medida de la convergencia del SG.
* Regularizaci�n en SG.
* Online Learning: introducci�n, motivaci�n, retos, pros y contras. Utilizaci�n del Stochastic Gradient Ascent para online learning. Paralelismo.


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[7_1_Scaling & Online Learning Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/7.%20Scaling%20%26%20Online%20Learning/7_1_Scaling%20%26%20Online%20Learning%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[7_2_Scaling & Online Learning Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/7.%20Scaling%20%26%20Online%20Learning/7_2_Scaling%20%26%20Online%20Learning%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Online Learning Assignment.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/3.%20Classification/7.%20Scaling%20%26%20Online%20Learning/Notebooks/01_Online%20Learning%20Assignment.ipynb)|Pr�ctica|Implementaci�n Stochastic Gradient Ascent|