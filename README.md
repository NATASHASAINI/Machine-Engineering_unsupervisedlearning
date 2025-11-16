 Customer Segmentation Using Unsupervised Clustering Algorithms

🚦 Steps Used: From Introduction to Output

1. Import Required Libraries
2. Load and Inspect the Data
Load the customer data from a CSV file.
Preview the first few rows to understand the structure.

3. Feature Selection and Scaling
Select relevant features for clustering.
Standardize the features to have zero mean and unit variance.

4. KMeans Clustering
Use the Elbow Method to determine the optimal number of clusters.
Fit KMeans and assign cluster labels.

5. Visualize KMeans Clusters

6. Hierarchical (Agglomerative) Clustering
Plot dendrogram to visualize hierarchical clustering.
Fit Agglomerative Clustering and assign labels.

7. Gaussian Mixture Model (GMM) Clustering
Fit GMM and assign cluster labels.

8. DBSCAN Clustering
Fit DBSCAN and assign cluster labels.

9. Cluster Evaluation
Calculate Silhouette Score (higher is better).
Calculate Davies-Bouldin Score (lower is better).

10. Interpretation and Output
KMeans had the highest Silhouette Score, indicating the best-defined clusters.
GMM had the lowest Davies-Bouldin Score, indicating the most compact and well-separated clusters.
DBSCAN did not find meaningful clusters with the current parameters (all points assigned to one cluster).

🏁 Conclusion

KMeans is recommended for this dataset based on Silhouette Score.

GMM is also a strong candidate based on Davies-Bouldin Score.

DBSCAN parameters may need tuning for meaningful results.
