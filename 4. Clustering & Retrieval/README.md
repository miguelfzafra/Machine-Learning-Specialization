# 4. Clustering & Retrieval

Esta carpeta contiene los apuntes y ejercicios del cuarto curso de la especializaci�n: **Clustering & Retrieval**.
 
## �ndice

| Semana | Descripci�n|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/1.%20Welcome) | Welcome |
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search) | Nearest Neighbor Search |
| [Semana 3](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means) | 3. Clustering with K-Means |
| [Semana 4](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models) | 4. Mixture Models |



## 1. Welcome

**Contenido**

* Introducci�n al curso. Contenido y objetivos.

**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[1_1_Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/1.%20Welcome/1_1_Intro%20Slides.pdf)|Teor�a|Introducci�n al curso.|




## 2. Nearest Neighbor Search

**Contenido**

* Introducci�n a Document Retrieval. Document Retrieval mediante K-NN.
* 1-NN y K-NN. Algoritmos. Elementos cr�ticos: representaci�n de los documentos y medida de la distancia.
* Representaci�n de documentos: Bag of words, TF-IDF.
* M�tricas de distancia: Eucl�dea, Scaled Euclidean, Similarity, Cosine Similarity. Normalizaci�n (motivaci�n y usos). Otras m�tricas. Combinaci�n de m�tricas.
* KD-Trees: motivaci�n, construcci�n, funcionamiento, elecci�n de diferentes decisiones (dimensiones en las que dividir, valores, stop value). Diferentes heur�sticos.
* B�squeda de NN con KD-Trees. Comparaci�n y complejidad. Approximate K-NN search con KD-Trees.
* Locally Sensitive Hashing para Approximate NN search. Motivaci�n (limitaciones de KD-Trees). Funcionamiento. Implementaci�n pr�ctica: retos. Mejora de la eficiencia. Caso de m�s de 2 dimensiones. Uso de m�ltiples Hash Tables para mayor eficiencia.



**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[2_1_Retrieval Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/1_1_Retrieval%20Intro%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[2_2_Retrieval Intro Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/1_2_Retrieval%20Intro%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_Nearest Neighbors Features and Metrics.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/Notebooks/01_Nearest%20Neighbors%20Features%20and%20Metrics.ipynb)|Pr�ctica|�n�lisis diferentes m�tricas y features|
|[02_NN LSH Implementation.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/Notebooks/02_NN%20LSH%20Implementation.ipynb)|Pr�ctica|Implementaci�n LSH.|


## 3. Clustering with K-Means


**Contenido**

* Introducci�n al clustering. Motivaci�n. Comparaci�n con aprendizaje supervisado.
* Definici�n de un cluster. Posibles retos.
* K-Means: asunciones y funcionamiento. Algoritmo. Utilizaci�n de coordinate descent para llevarlo a cabo. Convergencia. Smart inicialization (K-Means++). Medici�n de la calidad del clustering y elecci�n del n�mero de clusters.
* MapReduce: funcionamiento, motivaci�n. Ejemplo con word count. Aplicaci�n a K-Means y consideraciones pr�cticas. Mejora de la performance: combiners.
* Otros ejemplos de utilidad del clustering. 


**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[3_1_KMeans Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means/3_1_KMeans%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[3_2_KMeans Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means/3_2_KMeans%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[01_KMeans with text data.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means/Notebooks/01_KMeans%20with%20text%20data.ipynb)|Pr�ctica|Implementaci�n Kmeans.|



## 4. Mixture Models

**Contenido**

* Introducci�n al clustering con approach probabil�stico. Motivaci�n. Limitaciones de K-Means.
* Distribuciones gaussianas. Ejemplo pr�ctico con distribuciones. Media, varianza, covarianzas... (par�metros).
* Mixture of gaussians: modelo de clustering como un mixture de distribuciones gaussianas. T�rminos Prior y Likelihood. Aplicaci�n a text clustering.
* Estimaci�n de soft assignments con EM. Explicaci�n. Motivaci�n. Aplicaci�n del teorema de Bayes.
* Convergencia de EM. Inicializaci�n. Overfitting. Problemas en muchas dimensiones.
* Relaci�n con K-Means.

**Materiales**

|Archivo|Tipo|Descripci�n|
|-------|----|--------|
|[4_1_Mixture Models EM Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/4_1_Mixture%20Models%20EM%20Slides.pdf)|Teor�a|Diapositivas de teor�a.|
|[4_2_Mixture Models EM Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/4_2_Mixture%20Models%20EM%20Notes.pdf)|Teor�a|Apuntes de teor�a.|
|[1_EM for GMM.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/Notebooks/1_EM%20for%20GMM.ipynb)|Pr�ctica|Implementaci�n GMM con EM|
|[2_EM with text data.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/Notebooks/2_EM%20with%20text%20data.ipynb)|Pr�ctica|Ejemplo con text data. Covarianza diagonal e inicializaci�n con K-Means.|
