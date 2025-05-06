
![alt text](https://certificaciones.greatplacetowork.com.py/hubfs/Ucom_logo_22.png)

# Proyecto final -  Topicos especiales
## 1. Título tentativo del proyecto
Clasificación temática de artículos científicos sobre redes neuronales
mediante modelos de lenguaje preentrenados.
## 2. Integrantes
* Mónica Fleitas
* Carlos Bustamante
* Zulema Silguero

## 3. Planteamiento del problema
En la actualidad, el volumen de artículos científicos relacionados con redes
neuronales artificiales crece exponencialmente, lo cual dificulta la
organización y acceso eficiente a información relevante por parte de
investigadores y profesionales. Muchos de estos textos abordan
aplicaciones diversas, desde visión por computadora hasta procesamiento
del lenguaje natural, sin embargo, suelen encontrarse dispersos en bases
de datos científicas con etiquetado deficiente o inexistente, lo cual dificulta
el relevamiento de datos a la hora de realizar trabajos de investigación.
Este proyecto busca resolver este problema mediante la clasificación
automática de artículos científicos según la temática específica de la
aplicación de redes neuronales.

### Corpus o datos a utilizar
Obtener los datos de las presentaciones cientificas de la conacyt.

### Técnica(s) que planeas implementar
* Embeddings (Word2Vec, FastText) LSTM, GRU
* Modelos preentrenados (BERT, RoBERTa, SciBERT)
Vamos a centrarnos en modelos preentrenados como SciBERT, especializado en
texto científico, pero podemos hacer comparativas con técnicas más clásicas o
embeddings.
* Implementacion de un RAG utilizando los trabajos cientificos de redes neuronales 

## 4. Resultados esperados
Esperamos construir un sistema capaz de clasificar artículos científicos según
su temática principal relacionada con las aplicaciones de redes neuronales.
Para evaluar el rendimiento del sistema, se usará una métrica de clasificación
multiclase como:
* Exactitud (Accuracy)
* F1-Score macro y micro
* Matriz de confusion

Ver documento Analisis Tematico Automatizado de Presentaciones Cientificas de la Conacyt [aqui](Analisis_Tematico_Automatizado_de_Presentaciones_Cientificas_del_Sitio_de_CONACYT.pdf) 

