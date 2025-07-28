# 📊 Phase 4: SVD + PCA – Dimensionality Reduction and Clustering

## 🗂 Dataset

- **Name**: 20 Newsgroups
- **Source**: Fetched using `sklearn.datasets.fetch_20newsgroups`
- **Description**: Collection of ~18,000 newsgroup posts on 20 topics

##  Tasks Completed

### ✅ TF-IDF Vectorization
- Transformed raw text into a high-dimensional sparse matrix using **TF-IDF**.

### ✅ Dimensionality Reduction
- Applied **Truncated SVD** to reduce dimensions from 10,000 → 2.
- Visualized the top 2 components using a 2D scatter plot.

### ✅ Clustering (Optional but completed)
- Used **KMeans** to cluster the reduced 2D vectors into 20 groups.
- Evaluated clustering performance with:
  - **Silhouette Score**
  - **Adjusted Rand Index (ARI)**
  - Visual comparison of predicted clusters vs actual labels
