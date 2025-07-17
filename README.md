# Análisis de Factores de Riesgo en Startups Tecnológicas con Aprendizaje No Supervisado

## 📌 Objetivo del Estudio

El propósito de este estudio es **identificar factores de riesgo en startups tecnológicas en etapas tempranas** mediante técnicas de *Aprendizaje Automático no supervisado*. Se busca ofrecer una segmentación significativa de empresas emergentes a partir de variables cuantitativas y categóricas relevantes, tales como:

- Financiamiento recibido  
- Tracción digital  
- Número de rondas de inversión  
- Tipo de inversores

## ⚙️ Metodología

Para abordar la problemática, se diseñó un modelo de **clusterización** utilizando y comparando los siguientes algoritmos:

- **K-Means**  
- **Gaussian Mixture Models (GMM)**  
- **HDBSCAN**

### 🔧 Preprocesamiento

Se aplicaron diversas técnicas de preprocesamiento:

- Transformaciones logarítmicas  
- Estandarización de variables numéricas  
- Codificación de variables categóricas

### 📊 Evaluación de Clústeres

Se emplearon métricas de validación interna para evaluar la calidad de los agrupamientos:

- Coeficiente de **Silhouette**  
- Índice de **Calinski-Harabasz**  
- Índice de **Davies-Bouldin**

Además, se utilizaron técnicas de reducción de dimensionalidad para la visualización de los resultados:

- **PCA (Principal Component Analysis)**  
- **t-SNE (t-Distributed Stochastic Neighbor Embedding)**

## 📈 Resultados

El algoritmo **K-Means**, con un valor de **K = 2**, proporcionó la mejor combinación de cohesión y separación entre clústeres. También demostró mayor coherencia visual. Esta segmentación permitió identificar dos perfiles principales:

1. **Startups en etapa temprana**: bajos niveles de inversión y tracción digital.  
2. **Startups en etapa de crecimiento**: mayor financiamiento, equipos consolidados y fuerte presencia en redes profesionales.

## 📊 Visualización de Clústeres

## 📊 Visualización de Clústeres: K-Means con t-SNE

![Visualización K-Means t-SNE](https://github.com/davisclick/Analisis-de-Factores-de-Riesgo-en-la-Inversion-en-Startups-Tecnologicas/raw/main/comparativa_grafica_pca_tsne/k_means_tsne.png)

*Figura: Agrupamiento con K-Means (K=2) visualizado mediante t-SNE.*



## ✅ Conclusiones

Este estudio demuestra que es viable utilizar modelos no supervisados para segmentar startups tecnológicas según su riesgo potencial. Los resultados ofrecen una herramienta útil para **la toma de decisiones estratégicas por parte de inversores, aceleradoras e instituciones de apoyo al emprendimiento**.

## 🧠 Tecnologías utilizadas

- Python  
- Scikit-learn  
- HDBSCAN  
- Matplotlib / Seaborn  
- PCA / t-SNE  
- Pandas / NumPy



