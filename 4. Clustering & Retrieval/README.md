# 4. Clustering & Retrieval

Esta carpeta contiene los apuntes y ejercicios del cuarto curso de la especialización: **Clustering & Retrieval**.
 
## Índice

| Semana | Descripción|
|----------|-------------|
| [Semana 1](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/1.%20Welcome) | Welcome|
| [Semana 2](https://github.com/miguelfzafra/Machine-Learning-Specialization/tree/master/4.%20Clustering%20%26%20Retrieval/2.%20Nearest%20Neighbors%20Search) | Nearest Neighbor Search|


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
