
# 🌱 NPK

Este repositorio contiene código, datos e imágenes asociados a un sistema para aproximar el diagnóstico del estado de salud de cultivos mediante sensores NPK, imágenes multiespectrales y modelos computacionales.  
El objetivo principal es **predecir el índice de vegetación de diferencia normalizada (NDVI)** a partir de concentraciones de macronutrientes en el suelo (Nitrógeno, Fósforo y Potasio).

---

## 📂 Estructura del repositorio

El repositorio está organizado en carpetas principales, cada una con un propósito específico:


### 📁 `code/`
Incluye los **scripts en Python**
El codigo: Análisis y entrenamiento, es el código principal donde se encuentra **Análisis previo, preparación de datos** y **Entrenamiento**.

---

### 📁 `modelo_exportado/`
Contiene el **modelo final entrenado** (en formato `.joblib`).  
Este modelo puede cargarse directamente para realizar predicciones sin necesidad de reentrenar.

---

### 📁 `dataset/`
Incluye los **datos recopilados** durante el proyecto:
 
  - Valores interpolados de N, P y K  
  - NDVI calculado a partir de imágenes multiespectrales  
  - Coordenadas geográficas  
  - Variable de distancia normalizada  





