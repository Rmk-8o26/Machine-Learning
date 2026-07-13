# Mall Customer Segmentation

Segment mall customers into groups using **4 clustering algorithms** for targeted marketing insights.

## Algorithms Compared
1. **K-Means** — Centroid-based clustering
2. **Gaussian Mixture Models (GMM)** — Probabilistic clustering
3. **Agglomerative Clustering** — Hierarchical clustering
4. **DBSCAN** — Density-based clustering

## Pipeline
- Feature scaling (MinMax, Standard)
- Clustering with each algorithm
- Silhouette score evaluation
- Dendrogram visualization (hierarchical)

## Dataset
- `Mall_Customers.csv` — 200 rows
- Features: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1–100)

## Requirements
```
pip install -r requirements.txt
```
