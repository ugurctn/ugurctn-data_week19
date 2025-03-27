# ugurctn-data_week19

# Crypto Clustering with K-Means and PCA

This project applies machine learning techniques to analyze and cluster cryptocurrencies based on their performance data. It demonstrates how unsupervised learning — specifically K-Means clustering — can be used in combination with dimensionality reduction (PCA) to uncover patterns and group similar cryptocurrencies together.

## 📊 Project Overview

Using historical crypto market data, we:
- Preprocess and scale the data
- Reduce dimensions using **Principal Component Analysis (PCA)**
- Apply **K-Means clustering** to both the original and reduced datasets
- Visualize the results using **hvPlot** and **Matplotlib**
- Compare clustering outcomes with and without PCA

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas & NumPy
- Scikit-learn
- hvPlot
- Matplotlib

## 🧪 Machine Learning Techniques

- **StandardScaler** for data normalization
- **PCA** for dimensionality reduction
- **KMeans** for clustering
- **Elbow Method** to determine the optimal number of clusters (k)

## 📈 Visualizations

- Elbow curves for both scaled and PCA data
- Cluster scatter plots using:
  - First two features of the original scaled data
  - Principal components from PCA

## 🔍 Key Insights

- PCA-reduced clustering showed tighter and more defined clusters, making visual interpretation easier.
- While PCA reduces data complexity, it preserves most of the important variance needed for effective clustering.
- Comparing both methods helped reinforce the value of feature reduction in exploratory data analysis.

## 🚀 How to Run

1. Clone the repository or download the notebook file.
2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib hvplot
