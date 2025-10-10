# 🎵 AmazonMusicCluster

  
📁 Overview  
This dataset contains detailed metadata for a selection of songs and their associated artists. It is designed to support music analytics, recommendation systems, clustering experiments, and genre-based exploration. 

📊 Analytical Techniques
Each row represents a unique song with attributes spanning audio features, artist popularity, and genre classification  
- Feature Selection: Dropping redundant or low-variance features using correlation matrices and domain knowledge
- Outlier Detection: Using IQR and z-score methods to remove anomalies
- Clustering Analysis:
- Benchmarking algorithms with Silhouette Score and Davies-Bouldin Index
- Visualizing clusters using PCA and t-SNE projections
- Genre Profiling: Aggregating features by genre to identify stylistic patterns
- Popularity Modeling: Exploring relationships between audio features and song/artist popularity
- Temporal Analysis: Studying trends over time using release dates and tempo evolution  
  
🧪 Use Cases  
- Clustering songs by genre, mood, or acoustic profile 
- Building recommendation engines based on audio features  
- Analyzing artist popularity trends over time  
- Visualizing feature distributions (e.g., danceability vs. energy)   

🧪 Sample Insights 
- Songs with high acousticness and instrumentalness tend to belong to niche genres like chill guitar or ambient.
- High valence and tempo are common in danceable genres like merengue.
- Artist popularity does not always correlate with song popularity, especially for older releases.

🐍 Python Libraries
- pandas: For data loading, cleaning, and manipulation
- NumPy: For numerical operations and feature transformations
- matplotlib / seaborn: For visualizing distributions, correlations, and trends
- scikit-learn: For clustering, dimensionality reduction, and feature scaling
- KMeans, DBSCAN, AgglomerativeClustering
- PCA, t-SNE, UMAP
- StandardScaler, MinMaxScaler
- Plotly / Streamlit: For interactive dashboards and exploratory visualizations


