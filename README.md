# 📉 Reducción de Dimensionalidad con SVD y PCA (UCI HAR Dataset)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1u3DNiTIXCoSMFy4CwV85VadqNve1JwGB?usp=sharing)

Este proyecto explora la aplicación de fundamentos de **Álgebra Lineal** para optimizar el análisis de datos masivos. Se implementan técnicas de **Descomposición en Valores Singulares (SVD)** y **Análisis de Componentes Principales (PCA)** para reducir la dimensionalidad de un dataset de reconocimiento de actividades humanas (UCI HAR), manteniendo la varianza explicada más significativa.

## 📄 Descripción del Proyecto

El objetivo principal es demostrar cómo las transformaciones lineales y la descomposición matricial permiten simplificar conjuntos de datos complejos (sensores de acelerómetros y giroscopios) sin perder información crítica, facilitando su posterior clasificación o visualización.

**Documentación completa:** Puedes leer el análisis matemático detallado y las conclusiones en el [Reporte Técnico (PDF)](./Reporte%20Técnico%20-%20Grupo%201.pdf).

## 🛠️ Tecnologías y Conceptos

* **Lenguaje:** R (Ejecutado en Jupyter Notebook/Colab)
* **Librerías:** `data.table`, `ggplot2`, `dplyr`
* **Conceptos Matemáticos:**
    * Matriz de Covarianza
    * Valores y Vectores Propios (Eigenvalues/Eigenvectors)
    * Descomposición en Valores Singulares (SVD)
    * Proyección ortogonal y reducción de ruido

## 📊 Resultados Clave

El análisis permitió reducir el dataset original de múltiples dimensiones a componentes principales que capturan la mayor parte de la varianza, optimizando el costo computacional para tareas de Machine Learning.

## 📂 Estructura del Repositorio

* `Analisis_PCA_SVD.ipynb`: Código fuente con la implementación paso a paso en R.
* `Reporte Técnico - Grupo 1.pdf`: Documento académico con el marco teórico y justificación matemática.

## 🎓 Contexto Académico

Proyecto desarrollado para la materia de **Álgebra Lineal** en la **ESPOL (Escuela Superior Politécnica del Litoral)**.

**Autores:**
* José Paladines Sánchez
* Edwin Hernández Triviño
* Jeanpoul Larena Alcívar
* Julio Becerra Pozo
* Rafaela Quiñonez Abarca
* Mateo Saltos Moreira

---
*Este proyecto demuestra la aplicación práctica de teoremas matemáticos en Data Science.*
