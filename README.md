# Hotel Market Segmentation Analysis

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen)](https://jmalfaro2019.github.io/hotel-clustering-analysis/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

An unsupervised learning project that applies advanced clustering techniques to segment hotels based on their services, amenities, and pricing structure, revealing natural groupings beyond traditional star ratings.

## 🚀 Key Features

- **PCA Analysis**: Dimensionality reduction with 67.1% variance explained
- **Hierarchical Clustering**: Dendrograms and comparative linkage methods
- **Optimized K-Means**: Determination of the optimal K using the elbow method and silhouette
- **Rigorous Validation**: Silhouette score (0.453) and Adjusted Rand Index (0.179)
- **Advanced Visualization**: Comparison of clusters vs. star rating

## 📊 Key Results

| Metric | Result | Interpretation |
|---------|-----------|----------------|
| Optimal Clusters | 6 | Natural segmentation identified |
| Silhouette Score | 0.453 | Good clustering quality |
| ARI vs Stars | 0.179 | Low correlation with traditional classification |
| PCA Variance | 67.1% | Effective 2D representation |

## 🛠️ Technologies Used

- **Python 3.8+**
- **Libraries**: scikit-learn, pandas, NumPy, SciPy, matplotlib, seaborn
- **Algorithms**: PCA, Hierarchical Clustering, K-Means, K-Means++
- **Metrics**: Silhouette Score, Adjusted Rand Index, Inertia

## 📁 Project Structure

```
hotel-clustering-analysis/
├── notebooks/
│ ├── hotel_clustering_analysis.ipynb
| └── hotels.csv
├── docs/
│ ├── hotel_clustering_report.pdf
│ └── technical_documentation.pdf
├── data/
└── index.html # Project website
```
## ⚡ Installation and Use

# Clone the repository
```
git clone https://github.com/jmalfaro2019/hotel-clustering-analysis.git
cd hotel-clustering-analysis
```
# Install dependencies
```
pip install -r requirements.txt
```
# Run the analysis
```
jupyter notebook notebooks/hotel_clustering_analysis.ipynb
```

## 🔗 [View Project on GitHub Pages](https://jmalfaro2019.github.io/hotel-clustering-analysis/)

📄  **Full Report**
📋  [Download PDF Report](docs/hotel_clustering_report.pdf)

## 👨‍💻 Author
**Jose Alfaro** - [GitHub](https://github.com/jmalfaro2019) - [LinkedIn](https://www.linkedin.com/in/jose-miguel-alfaro-castillo-334327291)

### ⭐ Did you like this project? Give the repository a star!
