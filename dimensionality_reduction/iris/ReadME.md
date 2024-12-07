
###### Dimensionality Reduction on Iris Dataset with PCA and KPCA
This repository demonstrates the use of Principal Component Analysis (PCA) and Kernel Principal Component Analysis (KPCA) for dimensionality reduction and 
visualization of the Fisher Iris dataset. These techniques transform the high-dimensional data into a lower-dimensional space while preserving the most critical variance or 
patterns in the data.


🌸 Problem Statement
The Iris Dataset is a well-known dataset often used for testing and demonstrating machine learning techniques. The goal of this project is to:

* Reduce the dimensionality of the dataset while retaining essential features for visualization and analysis.
* Compare the linear transformation of PCA with the nonlinear transformation provided by KPCA.

Techniques
Principal Component Analysis (PCA)
* Linear technique for reducing dimensions by finding the directions (principal components) that maximize variance in the data.
* Features are transformed into a new coordinate system aligned with the directions of maximum variance.
Kernel Principal Component Analysis (KPCA)
Extends PCA to capture non-linear relationships by applying kernel methods.
Kernels used:
* Radial Basis Function (RBF) Kernel
