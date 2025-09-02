
# 🌱 NPK

Este repositorio contiene código, datos e imágenes asociados a un sistema para aproximar el diagnóstico del estado de salud de cultivos mediante sensores NPK, imágenes multiespectrales y modelos computacionales.  
El objetivo principal es **predecir el índice de vegetación de diferencia normalizada (NDVI)** a partir de concentraciones de macronutrientes en el suelo (Nitrógeno, Fósforo y Potasio).

---

## 📂 Estructura del repositorio

El repositorio está organizado en carpetas principales, cada una con un propósito específico:

### 📁 `images/`
Contiene las **imágenes multiespectrales** utilizadas en el estudio, capturadas mediante dron.  
Estas imágenes fueron la base para calcular índices de vegetación como el NDVI.

---

### 📁 `code/`
Incluye los **scripts en Python**

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




Para ejecutar los scripts se recomienda tener instalado **Python 3.10+** junto con las siguientes librerías:

