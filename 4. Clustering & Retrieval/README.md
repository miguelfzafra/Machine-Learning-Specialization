# 4. Clustering & Retrieval

Esta carpeta contiene los apuntes y ejercicios del cuarto curso de la especializaci�n: **Clustering & Retrieval**.
 
## �ndice

| Semana | Descripci�n|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/1.%20Welcome) | Welcome|
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search) | Nearest Neighbor Search|


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
