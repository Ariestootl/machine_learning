# 🔥🔥 Dimensionality Reduction and Clustering on MNIST Dataset 🔥🔥

| 📜 **Summary** |
|-----------------------------------|
| This repository explores dimensionality reduction techniques, including PCA, Kernel PCA (KPCA), and t-SNE, applied to the MNIST dataset. After reducing dimensions, DBSCAN (Density-Based Spatial Clustering of Applications with Noise) is used to cluster the data. The goal is to uncover patterns in the high-dimensional dataset and evaluate the performance of clustering in the reduced-dimensional space.|

| 🖼️ Problem Statement |
|----------------------|
| The MNIST Dataset is a benchmark dataset containing grayscale images of handwritten digits (0-9). Each image is represented as a 784-dimensional feature vector (28x28 pixels). Due to its high dimensionality, the data is challenging to process efficiently without dimensionality reduction. |
| **Objectives:** |
| 👉 To reduce the dimensionality of the dataset for visualization and clustering. |
| 👉 To analyze clustering results after applying DBSCAN on reduced features. |


| 🖼️ Dimensionality Reduction Techniques |
|----------------------------------------|
| 👉  **1. Principal Component Analysis (PCA)**  |
| - Linear technique that projects data onto a lower-dimensional space while retaining maximum variance. |
| - Visualized the data in 2D and 3D using the top principal components. |
| 👉  **2. Kernel Principal Component Analysis (KPCA)** |
| - Non-linear extension of PCA, using kernel functions to map data into a higher-dimensional space before reducing dimensions. |
| - Explored kernels: Radial Basis Function (RBF). |
| 👉  **3. t-Distributed Stochastic Neighbor Embedding (t-SNE)** |
| - Non-linear dimensionality reduction technique that emphasizes preserving local structure. |
| - Used for 2D and 3D visualizations to identify clusters of digits. |
| 👉  **4. Clustering with DBSCAN** |
| - DBSCAN identifies clusters based on the density of points and is robust to noise. |
| - Applied DBSCAN on features reduced by PCA, KPCA, and t-SNE. |
| - Key parameters tuned: |
|   - **Epsilon (ε):** Maximum distance between two samples to consider them neighbors. |
|   - **MinPts:** Minimum number of points to form a dense region. |


