# 📊 Entrega 3: Naive Bayes  

## 🏫 Universidad del Valle de Guatemala - Campus Central  
**Curso:** Minería de Datos (CC3074) - Sección 10  
**Proyecto:** Proyecto #2  
**Grupo:** #1  

## 👥 Integrantes del Grupo #1  
- **Pablo Daniel Barillas Moreno** - *Carné No. 22193*  
- **Mathew Cordero Aquino** - *Carné No. 22982*  

---

## 📌 Descripción del Proyecto  
Este proyecto corresponde a la **Entrega 3 del Proyecto #2** dentro del curso de **Minería de Datos**.  
En esta etapa, se desarrolló un modelo basado en **Naive Bayes** para la predicción y clasificación de precios de viviendas utilizando el conjunto de datos de Kaggle *"House Prices: Advanced Regression Techniques"*.  

**Objetivo principal:**  
Construir modelos de clasificación y regresión utilizando **Naive Bayes** y comparar su desempeño con modelos previos de regresión lineal y árboles de decisión.

---

## 📊 Metodología Aplicada  

1. **Preprocesamiento de Datos**  
   - Manejo de valores faltantes en variables numéricas y categóricas.  
   - Conversión de variables categóricas en factores.  
   - Normalización y estandarización de datos relevantes.  
   
2. **Modelado con Naive Bayes**  
   - Conversión de la variable `SalePrice` en categorías (`barata`, `media`, `cara`).  
   - Entrenamiento del modelo Naive Bayes para clasificación.  
   - Predicción y evaluación en el conjunto de prueba.  

3. **Evaluación del Modelo**  
   - Construcción de matriz de confusión.  
   - Análisis de métricas de precisión, recall y F1-score.  
   - Comparación de desempeño con modelos de regresión lineal y árboles de decisión.  

4. **Validación Cruzada y Ajuste de Hiperparámetros**  
   - Implementación de validación cruzada para mejorar el desempeño del modelo.  
   - Prueba con distintos valores de hiperparámetros (`laplace`, `usekernel`).  

---

## 🛠 Tecnologías Utilizadas  

- **Lenguaje utilizado:** R  
- **Plataforma:** RStudio  
- **Paquetes utilizados:** `e1071`, `caret`, `tidyverse`  
- **Control de Versiones:** GitHub  

---

## 📢 Resultados Destacados  

✔️ Se implementó un **modelo de Naive Bayes** para clasificar las viviendas en categorías de precio.  
✔️ Se compararon los resultados con **modelos previos de regresión lineal y árboles de decisión**.  
✔️ Se construyó una **matriz de confusión** para evaluar la precisión del modelo.  
✔️ Se aplicó **validación cruzada** y ajuste de hiperparámetros para optimizar el rendimiento.  

---
