# A1.3 Solución de problemas y selección de características – SC3314

**Alumno:** Josué Berdeal  
**Matrícula:** 000635654  
**Materia:** Inteligencia Artificial (SC3314)  
**Profesor:** Dr. Antonio Martínez Torteya  
**Universidad:** Universidad de Monterrey  

## Descripción

Este repositorio contiene el desarrollo de un **modelo de regresión lineal múltiple** para predecir la calificación final de estudiantes a partir de variables demográficas y académicas.

El análisis aborda problemas comunes en datos reales como **colinealidad entre variables**, **valores atípicos** y **selección de características**, con el objetivo de construir un modelo con buen desempeño predictivo y fácil interpretación.

## Archivos

- 📘 **[Notebook (Jupyter)](A1.3_635654.ipynb)**  
  Desarrollo completo del análisis, incluyendo limpieza de datos, análisis exploratorio, selección de características, entrenamiento de modelos y conclusiones.

- 🌐 **[Reporte Web (HTML – EDA Automatizado)](A1.3_635654.html)**  
  Reporte generado con *ydata_profiling* para el análisis exploratorio automatizado del dataset.

- 📊 **[Dataset: Calificaciones](A1.3%20Calificaciones.csv)**  
  Conjunto de datos original con información académica y demográfica de los estudiantes.

- 📄 **[Reporte en PDF](A1.3_635654.pdf)**  
  Versión en PDF del reporte final.

## Notas metodológicas

Debido a la **alta correlación** observada entre las calificaciones parciales **G1** y **G2**, no se incluyeron ambas variables simultáneamente en el modelo final. En su lugar, se entrenaron **dos modelos independientes** para comparar su desempeño y seleccionar la variable con mayor poder predictivo.

Además, se realizó tanto un **análisis exploratorio manual** como un **análisis exploratorio automatizado**, con el fin de validar la calidad de los datos, detectar duplicados, verificar valores atípicos y respaldar las decisiones de selección de características.

## Integridad académica

Doy mi palabra que este trabajo fue realizado con integridad académica.
