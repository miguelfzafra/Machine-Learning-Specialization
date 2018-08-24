# 4. Clustering & Retrieval

Esta carpeta contiene los apuntes y ejercicios del cuarto curso de la especialización: **Clustering & Retrieval**.
 
## Índice

| Semana | Descripción|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/1.%20Welcome) | Welcome |
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search) | Nearest Neighbor Search |
| [Semana 3](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means) | 3. Clustering with K-Means |
| [Semana 4](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models) | 4. Mixture Models |



## 1. Welcome

**Contenido**

* Introducción al curso. Contenido y objetivos.

**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[1_1_Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/1.%20Welcome/1_1_Intro%20Slides.pdf)|Teoría|Introducción al curso.|




## 2. Nearest Neighbor Search

**Contenido**

* Introducción a Document Retrieval. Document Retrieval mediante K-NN.
* 1-NN y K-NN. Algoritmos. Elementos críticos: representación de los documentos y medida de la distancia.
* Representación de documentos: Bag of words, TF-IDF.
* Métricas de distancia: Euclídea, Scaled Euclidean, Similarity, Cosine Similarity. Normalización (motivación y usos). Otras métricas. Combinación de métricas.
* KD-Trees: motivación, construcción, funcionamiento, elección de diferentes decisiones (dimensiones en las que dividir, valores, stop value). Diferentes heurísticos.
* Búsqueda de NN con KD-Trees. Comparación y complejidad. Approximate K-NN search con KD-Trees.
* Locally Sensitive Hashing para Approximate NN search. Motivación (limitaciones de KD-Trees). Funcionamiento. Implementación práctica: retos. Mejora de la eficiencia. Caso de más de 2 dimensiones. Uso de múltiples Hash Tables para mayor eficiencia.



**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[2_1_Retrieval Intro Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/1_1_Retrieval%20Intro%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[2_2_Retrieval Intro Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/1_2_Retrieval%20Intro%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_Nearest Neighbors Features and Metrics.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/Notebooks/01_Nearest%20Neighbors%20Features%20and%20Metrics.ipynb)|Práctica|Ánálisis diferentes métricas y features|
|[02_NN LSH Implementation.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search/Notebooks/02_NN%20LSH%20Implementation.ipynb)|Práctica|Implementación LSH.|


## 3. Clustering with K-Means


**Contenido**

* Introducción al clustering. Motivación. Comparación con aprendizaje supervisado.
* Definición de un cluster. Posibles retos.
* K-Means: asunciones y funcionamiento. Algoritmo. Utilización de coordinate descent para llevarlo a cabo. Convergencia. Smart inicialization (K-Means++). Medición de la calidad del clustering y elección del número de clusters.
* MapReduce: funcionamiento, motivación. Ejemplo con word count. Aplicación a K-Means y consideraciones prácticas. Mejora de la performance: combiners.
* Otros ejemplos de utilidad del clustering. 


**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[3_1_KMeans Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means/3_1_KMeans%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[3_2_KMeans Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means/3_2_KMeans%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[01_KMeans with text data.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/3.%20Clustering%20with%20K-Means/Notebooks/01_KMeans%20with%20text%20data.ipynb)|Práctica|Implementación Kmeans.|



## 4. Mixture Models

**Contenido**

* Introducción al clustering con approach probabilístico. Motivación. Limitaciones de K-Means.
* Distribuciones gaussianas. Ejemplo práctico con distribuciones. Media, varianza, covarianzas... (parámetros).
* Mixture of gaussians: modelo de clustering como un mixture de distribuciones gaussianas. Términos Prior y Likelihood. Aplicación a text clustering.
* Estimación de soft assignments con EM. Explicación. Motivación. Aplicación del teorema de Bayes.
* Convergencia de EM. Inicialización. Overfitting. Problemas en muchas dimensiones.
* Relación con K-Means.

**Materiales**

|Archivo|Tipo|Descripción|
|-------|----|--------|
|[4_1_Mixture Models EM Slides.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/4_1_Mixture%20Models%20EM%20Slides.pdf)|Teoría|Diapositivas de teoría.|
|[4_2_Mixture Models EM Notes.pdf](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/4_2_Mixture%20Models%20EM%20Notes.pdf)|Teoría|Apuntes de teoría.|
|[1_EM for GMM.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/Notebooks/1_EM%20for%20GMM.ipynb)|Práctica|Implementación GMM con EM|
|[2_EM with text data.ipynb](https://github.com/miguelfzafra/Machine-Learning-Specialization/blob/master/4.%20Clustering%20%26%20Retrieval/4.%20Mixture%20Models/Notebooks/2_EM%20with%20text%20data.ipynb)|Práctica|Ejemplo con text data. Covarianza diagonal e inicialización con K-Means.|
