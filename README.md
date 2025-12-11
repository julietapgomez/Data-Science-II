# 📊 Proyecto Final – Data Science II

**Autora:** Julieta Gómez  
**Curso:** Coderhouse – Data Science II  
**Entrega final:** Diciembre 2025  

---

## 🧠 Descripción general

Este proyecto analiza los factores asociados a la adicción a redes sociales en estudiantes, combinando herramientas de exploración de datos, visualización, agrupamiento no supervisado y modelos de clasificación.

Se parte de un conjunto de datos con variables sobre el uso diario de redes, percepción de adicción, salud mental, sueño, edad y género, entre otras.  
El objetivo es descubrir patrones de comportamiento, identificar perfiles y predecir la probabilidad de adicción a partir de variables cuantificables.

---

## 🎯 Objetivos del análisis

- Analizar si el uso excesivo de redes sociales se relaciona con problemas de sueño y salud mental.
- Comparar comportamientos según género y percepción de adicción.
- Identificar grupos de estudiantes con patrones de uso similares.
- Entrenar modelos predictivos que permitan anticipar el riesgo de adicción.
- Evaluar y comparar modelos según métricas de clasificación.

---

## 🛠️ Herramientas y tecnologías

- **Python**
- Pandas / Numpy / Seaborn / Matplotlib / Plotly
- Scikit-learn (sklearn)
- Yellowbrick
- Statsmodels (ANOVA)
- Google Colab

---

## 🧱 Etapas del proyecto

1. **Planteo del problema y formulación de hipótesis**
2. **Análisis exploratorio de datos (EDA)**  
   - Distribuciones por variable  
   - Correlaciones  
   - Gráficos univariados, bivariados y multivariados
3. **Agrupamiento (K-Means) y reducción de dimensionalidad (PCA)**
4. **Modelado supervisado**  
   - Random Forest  
   - Árbol de Decisión  
   - Regresión Logística
5. **Evaluación de modelos y validación cruzada**
6. **Comparación y selección del modelo más robusto**
7. **Conclusiones y reflexiones finales**

---

## 📌 Resultados principales

- Se confirmó que los estudiantes que usan redes sociales más de 4 horas por día duermen menos y presentan más señales de malestar emocional.
- El género femenino tuvo mayor proporción de casos con adicción autodeclarada.
- El clustering identificó tres perfiles estudiantiles: saludable, intermedio y de riesgo.
- El modelo de **Árbol de Decisión** alcanzó un accuracy del **93.4%**, y el **Random Forest** del **92.5%**, mostrando gran capacidad para anticipar casos de adicción.
- La validación cruzada mostró resultados estables (accuracy medio ≈ 91%).

---

## 📊 Visualizaciones destacadas

- Gráficos de torta por género y uso de redes
- Gráficos de dispersión por horas de uso vs. sueño (coloreado por género)
- Mapa de calor de correlaciones
- Visualización de clústers mediante PCA
- Matriz de confusión del modelo Random Forest
- Gráfico de barras comparando accuracy de modelos

---

## 📁 Archivos del repositorio

| Archivo | Descripción |
|--------|-------------|
| `Entrega Final_DS_Julieta_Gómez.ipynb` | Notebook con todo el análisis realizado |
| `Entrega Final - Data Science II.pptx` | Presentación visual del proyecto |
| `Students Social Media Addiction.csv` | Dataset original analizado |

---

## 🧩 Conclusiones

Este proyecto permitió detectar patrones de riesgo asociados al uso excesivo de redes sociales entre estudiantes.  
El trabajo combinó análisis exploratorio, clustering y modelos de Machine Learning, demostrando cómo la ciencia de datos puede ser una herramienta útil para la **detección temprana de conductas de riesgo** en contextos educativos.

---

## 🚀 Posibles mejoras futuras

- Incorporar nuevas variables (rendimiento académico, relaciones interpersonales)
- Aplicar técnicas de optimización de hiperparámetros (GridSearchCV)
- Implementar interpretabilidad con SHAP para análisis por variable
