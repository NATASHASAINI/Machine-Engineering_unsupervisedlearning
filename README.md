 Customer Segmentation Using Unsupervised Clustering Algorithms
 
🚦 Steps Used: 

1. Import Required Libraries: Import all necessary Python libraries for data manipulation, visualization, and clustering.

3. Load and Inspect the Data: Load the customer data from a CSV file.Preview the first few rows to understand the structure and contents.

4. Feature Selection and Scaling:Select relevant features for clustering (e.g., Purchase Frequency, Spend, Monthly Visits, Loyalty Score).Standardize the features to have zero mean and unit variance for optimal clustering performance.

5. KMeans Clustering: Use the Elbow Method to determine the optimal number of clusters.Fit the KMeans algorithm and assign cluster labels to each customer.

6. Visualize KMeans Clusters: Create scatter plots to visualize the clusters formed by KMeans.

7. Hierarchical (Agglomerative) Clustering:Plot a dendrogram to visualize the hierarchical clustering process.Fit Agglomerative Clustering and assign cluster labels.

8. Gaussian Mixture Model (GMM) Clustering: Fit a Gaussian Mixture Model and assign cluster labels to each customer.

9. DBSCAN Clustering:Fit the DBSCAN algorithm and assign cluster labels.Note: With current parameters, DBSCAN assigned all points to a single cluster.

10. Cluster Evaluation:Silhouette Score: Higher values indicate better-defined clusters.Davies-Bouldin Score: Lower values indicate more compact and well-separated clusters.

11. Interpretation and Output: KMeans had the highest Silhouette Score, indicating the best-defined clusters.GMM had the lowest Davies-Bouldin Score, indicating the most compact and well-separated clusters.
DBSCAN did not find meaningful clusters with the current parameters (all points assigned to one cluster).

🏁 Conclusion
KMeans is recommended for this dataset based on the highest Silhouette Score.

GMM is also a strong candidate based on the lowest Davies-Bouldin Score.

DBSCAN parameters may need further tuning for meaningful results.
