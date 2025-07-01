# 🌍 Country Segmentation Using Hierarchical Clustering and PCA

This project applies Hierarchical Clustering to group countries based on socio-economic indicators like income, exports, child mortality, and health expenditure. PCA is used to reduce dimensionality and visualize the clusters in 2D.

---

## 📊 Project Highlights

- Used `StandardScaler` to normalize all features
- Dendrogram used to find optimal number of clusters
- Applied **Agglomerative Clustering** with Ward linkage
- Reduced dimensions using **PCA** for visualization
- Visualized results with:
  - Barplot (cluster sizes)
  - Boxplots (feature distribution per cluster)
  - Heatmap (cluster-wise feature averages)
  - PCA 2D scatter plot
- Evaluated with **Silhouette Score**

---

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- Pandas, NumPy
- Scikit-learn (PCA, clustering, scaling)
- Seaborn & Matplotlib
- Scipy (for dendrogram)

---

## 📁 Files

| File | Description |
|------|-------------|
| `Country Segmentation Using Hierarchical Clustering and PCA.ipynb` | Main notebook |
| `Country-data.csv` | Dataset |
| `README.md` | This project summary |

