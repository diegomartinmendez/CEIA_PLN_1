## CEIA_PLN_1
#### Universidad de Buenos Aires - https://www.uba.ar/
#### Facultad de Ingeniería - https://www.fi.uba.ar/
#### Laboratorio de Sistemas Embebidos - https://fi.uba.ar/investigacion/areas-de-investigacion/electronica/laboratorio-de-sistemas-embebidos 
#### Especialización en Inteligencia Artificial (CEIA) - https://www.fi.uba.ar/posgrado/carreras-de-especializacion/inteligencia-artificial
### Procesamiento del Lenguaje Natural I

Este repositorio contiene los desafíos que se deben entregar para aprobar la materia.

### **[Desafío 1](https://github.com/diegomartinmendez/CEIA_PLN_1/blob/main/Desafio_1_Diego_Mendez.ipynb)**

#### Descripción
El objetivo del trabajo es aplicar técnicas de procesamiento de lenguaje natural (PLN) sobre el dataset 20 Newsgroups, utilizando representaciones de texto basadas en Bag of Words y TF-IDF, clasificadores Naive Bayes (MultinomialNB y ComplementNB) y evaluaciones mediante métricas como el F1-score.

#### Contenido del notebook
- Importación de bibliotecas y configuración de entorno.
- Carga y preprocesamiento del dataset 20 Newsgroups desde sklearn.datasets.
- Vectorización de textos utilizando:
- CountVectorizer (BoW)
- TfidfVectorizer
- Cálculo de similitudes de coseno.
- Entrenamiento y evaluación de modelos de clasificación:
- Multinomial Naive Bayes
- Complement Naive Bayes
- Cálculo y comparación de métricas de rendimiento.

### **[Desafío 2](https://github.com/diegomartinmendez/CEIA_PLN_1/blob/main/Desafio_2_Diego_Mendez.ipynb)**

#### Descripción
El objetivo del desafío es desarrollar un sistema de generación de texto basado en redes neuronales recurrentes, entrenado con un corpus propio. Se exploran diversas arquitecturas y técnicas de entrenamiento para mejorar la calidad del texto generado.

#### Contenido del notebook
- Instalación y actualización de librerías esenciales (numpy, tensorflow, keras, gensim).
- Carga y preprocesamiento de corpus.
- Tokenización y creación de secuencias.
- Implementación de modelos secuenciales:
- SimpleRNN
- LSTM
- GRU
- Entrenamiento y ajuste de hiperparámetros.
- Generación de texto usando estrategias como beam search.
- Comparación de resultados entre modelos.

### **[Desafío 3](https://github.com/diegomartinmendez/CEIA_PLN_1/blob/main/Desafio_3_Diego_Mendez.ipynb)**

#### Descripción
El objetivo del desafío es construir un sistema secuencial encoder-decoder utilizando redes neuronales recurrentes (RNN, LSTM, GRU) para resolver una tarea de generación o traducción de texto. Se entrena el modelo con pares de oraciones, implementando un pipeline completo que incluye preprocesamiento, entrenamiento e inferencia.

#### Contenido del notebook
- Preprocesamiento de datos:
  - Tokenización
  - Creación de diccionarios (word2idx / idx2word)
  - Padding y codificación
- Implementación del modelo secuencial tipo Encoder-Decoder con Keras:
  - Embedding
  - RNN / LSTM / GRU
  - Mecanismo de inferencia paso a paso
- Generación de texto por inferencia secuencial.
- Evaluación cualitativa de los resultados generados.

### **[Desafío 4](https://github.com/diegomartinmendez/CEIA_PLN_1/blob/main/Desafio_4_Diego_Mendez.ipynb)**

#### Descripción
En este trabajo se avanza en el desarrollo de sistemas de traducción automática y generación de lenguaje natural. Se utilizan pares de frases en español e inglés para entrenar un modelo encoder-decoder, incorporando embeddings preentrenados.

#### Contenido del notebook
- Instalación de herramientas externas (gdown) para descarga de datasets.
- Carga y exploración de corpus bilingüe.
- Tokenización y vectorización de frases.
- Creación de diccionarios word2idx y idx2word por idioma.
- Construcción del modelo encoder-decoder con Keras:
  - Capa de embeddings
  - LSTM / GRU
  - Decodificador paso a paso
- Entrenamiento con corpus de pares de frases.
- Evaluación del modelo con métricas como BLEU.
- Análisis cualitativo de los resultados generados.
