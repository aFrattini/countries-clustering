# Proyecto UD3 — Identificación de Países Más Necesitados

Este proyecto forma parte de la Unidad Didáctica 3 (UD3) del módulo **Sistemas de Aprendizaje Automáticos**, del curso de especialización en IA y Big Data, impartido en el IES de Teis (Vigo), bajo la tutoría de Vanesa Resúa Eiras.

El objetivo es identificar qué países se encuentran en mayor situación de pobreza a partir de datos socioeconómicos y de salud, aplicando técnicas de aprendizaje no supervisado, y evaluar si el uso de **PCA** resulta beneficioso para mejorar la calidad de la agrupación.

---

## 📦 Dataset

El conjunto de datos incluye información de **166 países**, con variables clave como:
- Mortalidad infantil
- Exportaciones e importaciones (% del PIB per cápita)
- Gasto en salud (% del PIB per cápita)
- Ingresos netos per cápita
- Inflación
- Esperanza de vida
- Número medio de hijos por mujer
- PIB per cápita

---

## ⚙️ Proceso

1. Importación y exploración del dataset.
2. Análisis exploratorio para descubrir relaciones entre variables.
3. Preprocesado de los datos para prepararlos para el modelado.
4. Determinación del número óptimo de clusters (método del codo, silhouette score).
5. Entrenamiento de modelos no supervisados: **K-Means** y **Clustering Jerárquico**.
6. Evaluación del impacto de aplicar reducción de dimensionalidad mediante **PCA**.
7. Interpretación de resultados y extracción de conclusiones claras.

---

## 📊 Resultados y conclusiones

- **Clustering Jerárquico** destacó por identificar de forma más precisa los países en situación de pobreza extrema, aunque su rendimiento también disminuyó tras aplicar PCA, mezclando grupos que antes estaban claramente diferenciados.
- **PCA** redujo las variables a 6 componentes que explican el 97% de la varianza, pero no mejoró ni la precisión ni el tiempo de ejecución.
- Entre los países más necesitados destacan: Afghanistan, Benin, Burkina Faso, Burundi, Cameroon, Chad, Congo, Gambia, Guinea, Haiti, Madagascar, Malawi, Mali, Mozambique, Niger, Sierra Leone, Tanzania, Togo, Uganda y Zambia.


---

## 📎 Notebook

👉 [Ver notebook en GitHub](https://github.com/aFrattini/countries-clustering/blob/main/countries-clustering.ipynb)
