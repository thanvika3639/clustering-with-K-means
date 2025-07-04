# clustering-with-K-means

🧪 Steps Performed
1. Load and Explore the Dataset
Imported CSV using pandas.

Explored the structure with df.info() and df.head().

2. Preprocessing
Selected only numerical columns:
Annual Income (k$) and Spending Score (1-100) for clustering.

3. Elbow Method to Determine Optimal K
Plotted Within-Cluster Sum of Squares (Inertia) for K = 1 to 10.

Identified the "elbow point" to find the best K.

4. K-Means Clustering
Applied KMeans algorithm with optimal K.

Cluster labels assigned to each customer.

5. Visualization
Scatter plot showing clusters with distinct colors.

X-axis: Annual Income, Y-axis: Spending Score

6. Evaluation
Calculated Silhouette Score to measure clustering quality.

📊 Outputs
Clustered Data: Each customer is assigned a cluster.

Scatter Plot: Visual depiction of customer segments.

Silhouette Score: Indicates how well the clusters are separated.
