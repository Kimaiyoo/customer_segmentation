# 🧠 Customer Segmentation using Unsupervised Learning

This project applies **unsupervised machine learning** to segment customers based on their demographics and spending behavior.  
We perform **EDA, feature engineering, dimensionality reduction, and clustering** to discover actionable customer groups.

---

## 📊 Project Workflow

- **Exploratory Data Analysis:** Summary statistics, missing value handling, age grouping, correlation analysis  
- **Data Cleaning & Preprocessing:** Remove duplicates, filter outliers, scale numeric features  
- **Feature Engineering:** Create new ratios, flag high-value customers, build pivot tables  
- **Visualization:** Histograms, scatter plots, boxplots, heatmaps to explore patterns  
- **Dimensionality Reduction:** PCA & t-SNE for visualizing high-dimensional patterns  
- **Clustering:** K-Means (with elbow method & silhouette score) and Hierarchical Clustering to identify groups  
- **Cluster Profiling:** Analyze average age, income, and spending score per cluster  

---

## 📈 Key Insights

- Identified **distinct customer segments** (e.g., high-spending younger groups vs. low-spending seniors)
- t-SNE produced clearer separation of clusters compared to PCA
- Results exported with cluster labels for use in marketing and analytics

---

## 🧰 Tech Stack

**Python** | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Scipy

---

## 🚀 How to Run

```bash
git clone https://github.com/Kimaiyoo/customer_segmentation.git
cd customer_segmentation
pip install -r requirements.txt
jupyter notebook customer_segmentation.ipynb
```
---
## 📌 Future Improvements

- Experiment with DBSCAN or Gaussian Mixture Models
- Add purchase history or additional customer attributes
- Build an interactive dashboard for real-time cluster exploration
