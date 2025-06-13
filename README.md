# 🎯 Customer Segmentation using Clustering

![PCA Visualization](reports/pca_plot.png) <!-- Add your actual image path -->

## 📌 Overview
Unsupervised learning project to segment e-commerce customers using RFM (Recency, Frequency, Monetary) analysis and K-means clustering. Identified high-value segments for targeted marketing.

## 🛠️ Tech Stack
- **Python**: scikit-learn, Pandas, Matplotlib/Seaborn
- **Algorithms**: K-means, PCA, Elbow Method, Silhouette Analysis
- **Data**: [Online Retail II Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

## 🚀 Key Steps
1. Engineered RFM features from transactional data
2. Optimized clusters using silhouette scores
3. Visualized segments with PCA and radar charts
4. Generated business strategies per segment

## 📂 Repository Structure
```bash
# Tree structure shown above
```

## 💡 How to Run
1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Execute Jupyter notebook:
```bash
jupyter notebook notebooks/Customer_Segmentation.ipynb
```

## 📊 Results
| Segment | Characteristics | Recommended Strategy |
|---------|-----------------|-----------------------|
| 0 | High recency, low spend | Win-back campaigns |
| 1 | High frequency, VIPs | Loyalty rewards |
| ... | ... | ... |

![Radar Chart](reports/radar_chart.png)
