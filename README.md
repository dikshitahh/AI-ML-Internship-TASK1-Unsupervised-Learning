# AI-ML-Internship-TASK1-Unsupervised-Learning

#ALGORITHM USED : K-Means Clustering

#Objective

The objective of this task is to understand the concept of Unsupervised Learning by implementing the K-Means Clustering algorithm. The model groups customers into different clusters based on their Annual Income and Spending Score without using labeled data.

#Dataset

Dataset Name: Mall Customers Dataset

The dataset contains information about mall customers, including:

- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

#Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

#Steps Performed

1. Imported the required libraries.
2. Loaded the Mall Customers dataset.
3. Explored the dataset using [head(), shape() and info()].
4. Checked for missing values.
5. Selected Annual Income and Spending Score as the features for clustering.
6. Visualized the customer distribution using a scatter plot.
7. Used the Elbow Method to determine the optimal number of clusters.
8. Applied the K-Means Clustering algorithm with (K = 5).
9. Visualized the customer clusters along with their centroids.
10. Saved the clustered dataset as a CSV file.


#Results

The following outputs were generated during the implementation:

- Customer Distribution Plot
- Elbow Method Graph
- K-Means Cluster Visualization
- Clustered Dataset (CSV)


#Comparison of Clustering Algorithms
--------------------------------------------------------------------------------------------------------------------
| Feature             | K-Means               | Hierarchical Clustering         | DBSCAN                           |
|---------------------|-----------------------|---------------------------------|----------------------------------|
| Type                | Centroid-based        | Hierarchical                    | Density-based                    |
| Number of Clusters  | User-defined (K)      | Determined using a dendrogram   | Automatically detected           |
| Speed               | Fast                  | Slower                          | Moderate                         |
| Handles Noise       | No                    | Limited                         | Yes                              |
| Best For            | Large datasets        | Small to medium datasets        | Arbitrary-shaped clusters        |
| Main Limitation     | Requires choosing K   | High computational cost         | Sensitive to parameter selection |
--------------------------------------------------------------------------------------------------------------------

#Conclusion

In this task, the K-Means Clustering algorithm was successfully implemented on the Mall Customers dataset. The Elbow Method was used to determine the optimal number of clusters, and customers were grouped into five distinct clusters based on their Annual Income and Spending Score. The results demonstrate how unsupervised learning can be used for customer segmentation and pattern discovery without requiring labeled data.
