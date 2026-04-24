# Análisis de Tópicos Latentes en Noticias con Apache Spark y LDA

Este proyecto aplica técnicas de **Procesamiento de Lenguaje Natural (NLP)** y **Aprendizaje Automático No Supervisado** para identificar temáticas predominantes en un corpus de noticias de la BBC. Se utiliza el framework **Apache Spark** para garantizar escalabilidad y eficiencia en el procesamiento de grandes volúmenes de datos.

## 🚀 Descripción del Proyecto
El objetivo principal es extraer tópicos latentes de un dataset de noticias (`bbc-news-data.csv`) mediante el algoritmo **LDA (Latent Dirichlet Allocation)**. 

### Características principales:
* **Pipeline de NLP:** Limpieza refinada de texto, eliminación de stopwords personalizadas y lematización con Spark NLP.
* **Vectorización:** Comparativa entre modelos basados en **CountVectorizer** y **TF-IDF**.
* **Evaluación:** Uso de métricas de **Log Likelihood** y **Log Perplexity** para determinar el número óptimo de tópicos ($k$).

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Framework de Big Data:** Apache Spark (PySpark 3.4.1)
* **NLP:** Spark NLP (5.3.2)
* **Documentación:** Reporte técnico en LaTeX.

## 📊 Resultados
El modelo final logró segmentar las noticias en categorías coherentes (Negocios, Tecnología, Política, etc.), permitiendo una reducción de dimensionalidad efectiva sobre el texto no estructurado. Se determinó que el uso de TF-IDF mejora significativamente la separación de los tópicos frente a simples conteos de frecuencia.

## 📁 Estructura del Repositorio
* `TP_Prog.ipynb`: Notebook con el flujo completo de datos y modelado.
* `bbc-news-data.csv`: Dataset utilizado (noticias de la BBC).
* `TP_Programacion_Funcional_Informe.pdf`: Informe detallado con fundamentación técnica y resultados.

## ✒️ Autor
* Juan Cruz Di Meglio - www.linkedin.com/in/juan-cruz-di-meglio

