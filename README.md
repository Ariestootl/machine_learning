# Advanced Computational Methods in Data Science (DS397): Machine Learning Implementations

🚧 **STATUS:** *Active Portfolio Project. This repository is continuously updated with new machine learning implementations and computational experiments.*

## 🧠 About the Developer
I am **Jose Aries E. De Los Santos**, a Data Science Ph.D. student and a University Lecturer at the Institute of Mathematics, College of Science, University of the Philippines Diliman, holding a Master of Science in Applied Mathematics degree. Driven by a passion for bridging theoretical mathematics with computational implementation, I built this repository as an open academic and pedagogical resource. 

By constructing these complex architectures and models from scratch, I aim to explore and share a deep, mechanistic understanding of how state-of-the-art models function beneath the abstractions of standard frameworks, serving both advanced research and educational purposes.

## 🔬 Project Overview
This repository contains a curated collection of machine learning algorithms and computational methods implemented as part of the DS397 course. The projects focus on both theoretical foundations and practical applications across various domains, including classification, regression, and dimensionality reduction.

The primary objective is to provide transparent, readable, and mathematically rigorous codebases for each method, utilizing standard datasets (e.g., Fisher Iris, MNIST, Taiwan Real Estate) to benchmark performance and demonstrate core data science principles.

## 🗂️ Repository Structure
```text
├── Classification/
│   ├── Neural Network Classification(Fisher Iris Dataset).ipynb
│   ├── Support Vector Machine Classification (Fisher Iris Dataset).ipynb
│   └── README.md
├── Dimensionality Reduction/
│   ├── DimReduce - MNIST.ipynb
│   ├── DimReduce2 - MNIST.ipynb
│   └── README.md
├── Linear Regression/
│   ├── Linear Regression (Taiwan House Price Prediction).ipynb
│   ├── Neural Network Regression.ipynb
│   ├── real_estate_taiwan.csv
│   └── ReadMe.md
├── Linear Regression via Gradient Descent/
│   ├── Linear Regressio via Gradient Descent.ipynb
│   └── README.md
├── Logistic Regression/
│   ├── social_network.ipynb
│   └── Social_Network_Ads.csv
├── Other Machine Problems/
│   ├── DS397_MP1_2a_DeLosSantosJoseAries.ipynb
│   ├── DS397_MP1_2b_DeLosSantosJoseAries.ipynb
│   ├── Machine Problem 2_1a.ipynb
│   ├── Machine Problem 2_2.ipynb
│   └── README.md
└── dimensionality_reduction/iris/
    ├── Kernel_Principal_Component_Analysis_Iris_Dataset.ipynb
    └── Principal_Component_Analysis_Iris_Dataset.ipynb
```

## 📐 Implemented Methods

### 1. Classification
*   **Neural Network Classification:** Built and evaluated on the Fisher Iris Dataset to categorize species based on morphological features.
*   **Support Vector Machines (SVM):** Margin-based classification demonstrating the mathematical application of optimal hyperplanes.

### 2. Regression Analysis
*   **Linear & Logistic Regression:** Predictive modeling on datasets such as Taiwan House Prices and Social Network Ads.
*   **Gradient Descent:** Implementations highlighting the optimization processes underlying linear regression.
*   **Neural Network Regression:** Exploring deep learning approaches to continuous variable prediction.

### 3. Dimensionality Reduction
*   **Principal Component Analysis (PCA):** Linear feature extraction and variance maximization, applied to the Iris dataset.
*   **Kernel PCA:** Non-linear dimensionality reduction extensions for mapping complex, inseparable data.
*   **MNIST Reductions:** Handling high-dimensional image datasets to improve computational efficiency and visualization.

## 🎯 Impact and Use Case
This repository is designed for data science students, researchers, and practitioners looking to solidify their understanding of fundamental machine learning algorithms. By applying these methods to real-world and benchmark datasets, it bridges the gap between statistical theory and computational engineering.

## 📝 How to Cite
If you utilize these architectures or educational notebooks in your research, study, or projects, please consider citing this repository:

**APA Format:**
> De Los Santos, J. A. E. (2023--Present). *Advanced Computational Methods in Data Science  Implementations*. GitHub. https://github.com/Ariestootl/machine_learning.git

**BibTeX:**
```bibtex
@software{delossantos_ds397_implementations,
  author = {De Los Santos, Jose Aries E.},
  title = {Advanced Computational Methods in Data Science Implementations},
  year = {2023--Present},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/Ariestootl/machine_learning.git}}
}
```
## 📚 References & Acknowledgments
The implementations, mathematical derivations, and theoretical foundations within this repository are heavily inspired by and built upon the knowledge from the following exceptional resources:

* Pilario, K. (n.d.). DS397 Advance computational methods in data science [Source Code]. GitHub. https://github.com/kspilario/DS397_comp

* Bishop, C. M. (2006). Pattern recognition and machine learning. Springer.

* Brunton, S. L., & Kutz, J. N. (2022). Data-driven science and engineering: Machine learning, dynamical systems, and control (2nd ed.). Cambridge University Press.

* Hastie, T., Tibshirani, R., & Friedman, J. (2009). The elements of statistical learning: Data mining, inference, and prediction (2nd ed.). Springer.

* James, G., Witten, D., Hastie, T., Tibshirani, R., & Taylor, J. (2023). An introduction to statistical learning: With applications in Python. Springer.

