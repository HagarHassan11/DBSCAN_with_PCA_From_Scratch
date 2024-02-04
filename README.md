# DBSCAN_with_PCA_From_Scratch
# Principal Component Analysis (PCA):

The project begins with implementing PCA for dimensionality reduction on the handwritten digits dataset. PCA is applied to reduce the number of features while retaining the essential information. The PCA function is implemented from scratch, including covariance matrix calculation, power iteration for eigenvalues and eigenvectors, and transformation of the data.

Three different scenarios are considered with varying numbers of principal components (40, 30,20,10 and 3). For each scenario, the original data is transformed and then reconstructed to measure the reconstruction error. The results provide insights into the trade-off between dimensionality reduction and information preservation.

# Density-Based Spatial Clustering of Applications with Noise (DBSCAN):
Next, a basic DBSCAN algorithm is implemented from scratch. The DBSCAN algorithm is applied to the standardized dataset, and the results are compared with scikit-learn's DBSCAN implementation. The basic DBSCAN implementation handles core points, expands clusters, and identifies noise points.
The comparison between the custom DBSCAN and scikit-learn's DBSCAN shows consistent results, validating the accuracy of the custom implementation.

# Integration of PCA and DBSCAN:
The project concludes by applying DBSCAN on the PCA-transformed data with three principal components. The clusters obtained from this combined approach are visualized in a 3D plot. The comparison between the custom and scikit-learn's DBSCAN on PCA-transformed data demonstrates the effectiveness of the overall approach in capturing underlying patterns in the digit dataset.

# Visualization:
Throughout the project, visualizations using matplotlib and seaborn are provided to enhance understanding. These visualizations include PCA results, reconstruction errors, and 3D plots of clustered data.

# Conclusion:
This project serves as a comprehensive exploration of dimensionality reduction using PCA and clustering using DBSCAN for handwritten digit recognition. The custom implementations, along with scikit-learn's library, are utilized to ensure accuracy and reliability. The results and visualizations presented in the project contribute to a better understanding of the interplay between dimensionality reduction and clustering in the context of digit recognition.




