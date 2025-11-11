# Hotel Market Segmentation Analysis

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen)](https://jmalfaro2019.github.io/hotel-clustering-analysis/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Proyecto de aprendizaje no supervisado que aplica técnicas avanzadas de clustering para segmentar hoteles basándose en sus servicios, amenities y estructura de precios, revelando agrupaciones naturales más allá de las clasificaciones tradicionales por estrellas.

## 🚀 Características Principales

- **Análisis PCA**: Reducción de dimensionalidad con 67.1% de varianza explicada
- **Clustering Jerárquico**: Dendrogramas y métodos de linkage comparativos
- **K-Means Optimizado**: Determinación del K óptimo mediante método del codo y silhouette
- **Validación Rigurosa**: Silhouette score (0.453) y Adjusted Rand Index (0.179)
- **Visualización Avanzada**: Comparación clusters vs clasificación por estrellas

## 📊 Resultados Destacados

| Métrica | Resultado | Interpretación |
|---------|-----------|----------------|
| Clusters Óptimos | 6 | Segmentación natural identificada |
| Silhouette Score | 0.453 | Calidad de clustering buena |
| ARI vs Estrellas | 0.179 | Baja correlación con clasificación tradicional |
| Varianza PCA | 67.1% | Representación efectiva en 2D |

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Librerías**: scikit-learn, pandas, NumPy, SciPy, matplotlib, seaborn
- **Algoritmos**: PCA, Hierarchical Clustering, K-Means, K-Means++
- **Métricas**: Silhouette Score, Adjusted Rand Index, Inertia

## 📁 Estructura del Proyecto

```
hotel-clustering-analysis/
├── notebooks/
│ ├── hotel_clustering_analysis.ipynb
| └── hotels.csv
├── docs/
│ ├── hotel_clustering_report.pdf
│ └── technical_documentation.pdf
├── data/
└── index.html # Página web del proyecto
```
## ⚡ Instalación y Uso

# Clonar el repositorio
```
git clone https://github.com/jmalfaro2019/hotel-clustering-analysis.git
cd hotel-clustering-analysis
```
# Instalar dependencias
```
pip install -r requirements.txt
```
# Ejecutar el análisis
```
jupyter notebook notebooks/hotel_clustering_analysis.ipynb
```

## 🔗 [Ver Proyecto en GitHub Pages](https://jmalfaro2019.github.io/hotel-clustering-analysis/)

📄  **Reporte Completo**
📋  [Descargar Reporte PDF](docs/hotel_clustering_report.pdf)

## 👨‍💻 Autor
**Jose Alfaro** - [GitHub](https://github.com/jmalfaro2019) - [LinkedIn](https://www.linkedin.com/in/jose-miguel-alfaro-castillo-334327291)

### ⭐ ¿Te gustó este proyecto? ¡Dale una estrella al repositorio!
