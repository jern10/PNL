#  Procesamiento de Lenguaje Natural - CEIA

Repositorio correspondiente a los desafíos prácticos de la materia **Procesamiento de Lenguaje Natural (PNL)** – CEIA 2026.

Autor: **Juan E. Ramos Nervi**

---

## Estructura del repositorio
```
PNL/
│
├── desafio_1.ipynb
├── desafio_2.ipynb
│
├── desafio_3/
│   └── desafio_3.ipynb
│
├── desafio_4/
│   └── desafio_4.ipynb
│
└── README.md
```

---

##  Desafíos

###  Desafío 1 – Vectorización y Similaridad de Documentos

- Dataset: **20 Newsgroups**
- Técnicas utilizadas:
  - Bag of Words
  - TF-IDF
  - Similaridad coseno
- Objetivos:
  - Representar documentos como vectores
  - Encontrar documentos similares
  - Clasificación con Naïve Bayes

---

###  Desafío 2 – Word Embeddings

- Dataset: Letras de canciones
- Técnicas utilizadas:
  - Entrenamiento de embeddings (Word2Vec / Gensim)
  - Similaridad entre palabras
  - Reducción de dimensionalidad (PCA / t-SNE)
- Objetivos:
  - Analizar relaciones semánticas
  - Visualizar clusters de palabras

---

###  Desafío 3 – Modelos de Lenguaje (Character-Level)

- Dataset: Texto literario (ej: *Veinte mil leguas de viaje submarino*)
- Modelos:
  - SimpleRNN
  - LSTM
  - GRU
- Técnicas:
  - Tokenización a nivel carácter
  - Entrenamiento secuencial
  - Generación de texto
  - Beam Search (determinístico y estocástico)
- Objetivos:
  - Modelar lenguaje carácter a carácter
  - Evaluar con **perplexity**
  - Analizar efecto de la temperatura

---

###  Desafío 4 – Question Answering Bot

- Implementación de un sistema de QA
- Componentes posibles:
  - Retrieval (búsqueda de contexto)
  - Modelos tipo transformer / embeddings
- Objetivos:
  - Responder preguntas sobre un corpus
  - Evaluar calidad de respuestas

---

##  Requisitos

```bash
pip install numpy scikit-learn matplotlib gensim torch
