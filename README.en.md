# Machine Learning Application for Risk Analysis in Tech Startups

## 📌 Study Objective

The purpose of this study is to **identify risk factors in early-stage tech startups** using *unsupervised machine learning techniques*. The goal is to provide a meaningful segmentation of emerging companies based on relevant quantitative and categorical variables, such as:

- Funding received  
- Digital traction  
- Number of investment rounds  
- Type of investors

## ⚙️ Methodology

To address this problem, a **clustering model** was designed by comparing the following algorithms:

- **K-Means**  
- **Gaussian Mixture Models (GMM)**  
- **HDBSCAN**

### 🔧 Preprocessing

Several preprocessing techniques were applied:

- Logarithmic transformations  
- Standardization of numerical variables  
- Encoding of categorical variables

### 📊 Cluster Evaluation

Internal validation metrics were used to assess the quality of the clustering:

- **Silhouette Coefficient**  
- **Calinski-Harabasz Index**  
- **Davies-Bouldin Index**

<h3 align="center">📈 Cluster Evaluation</h3>

<p align="center">
  <img src="https://github.com/davisclick/Analisis-de-Factores-de-Riesgo-en-la-Inversion-en-Startups-Tecnologicas/raw/main/comparatica_grafica_mejor_K/silhouette_score.png" width="30%" />
  <img src="https://github.com/davisclick/Analisis-de-Factores-de-Riesgo-en-la-Inversion-en-Startups-Tecnologicas/raw/main/comparatica_grafica_mejor_K/calinski_harabasz_index.png" width="30%" />
  <img src="https://github.com/davisclick/Analisis-de-Factores-de-Riesgo-en-la-Inversion-en-Startups-Tecnologicas/raw/main/comparatica_grafica_mejor_K/davies_bouldin_index.png" width="30%" />
</p>

<p align="center"><i>Silhouette Score · Calinski-Harabasz · Davies-Bouldin</i></p>

Additionally, dimensionality reduction techniques were used to visualize the clustering results:

- **PCA (Principal Component Analysis)**  
- **t-SNE (t-Distributed Stochastic Neighbor Embedding)**

## 📈 Results

The **K-Means algorithm**, with **K = 2**, provided the best combination of cohesion and separation between clusters. It also showed the most consistent visual results. This segmentation allowed the identification of two main profiles:

1. **Early-stage startups**: low levels of investment and digital traction.  
2. **Growth-stage startups**: higher funding, consolidated teams, and stronger presence in professional networks.

## 📊 Cluster Visualization with K-Means

### t-SNE

![K-Means t-SNE](https://github.com/davisclick/Analisis-de-Factores-de-Riesgo-en-la-Inversion-en-Startups-Tecnologicas/raw/main/comparativa_grafica_pca_tsne/k_means_tsne.png)

### PCA

![K-Means PCA](https://github.com/davisclick/Analisis-de-Factores-de-Riesgo-en-la-Inversion-en-Startups-Tecnologicas/raw/main/comparativa_grafica_pca_tsne/k_means_pca.png)

*Figures: Visual representations of the clustering with K-Means (K=2) using t-SNE and PCA, respectively.*

## ✅ Conclusions

This study shows that it is feasible to apply unsupervised models to segment tech startups based on their potential risk. The results offer a valuable tool for **strategic decision-making by investors, accelerators, and entrepreneurship support institutions**.

## 🧠 Technologies Used

- Python  
- Scikit-learn  
- HDBSCAN  
- Matplotlib / Seaborn  
- PCA / t-SNE  
- Pandas / NumPy
