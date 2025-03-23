# Clustering Algorithms — From Scratch and Explained

This repository presents a comprehensive walkthrough of major clustering algorithms, implemented from scratch using only Python and NumPy. Each algorithm is accompanied by visual demonstrations, highlighting its strengths, limitations, and ideal use cases.

The goal is both educational and practical: to deeply understand how clustering algorithms behave on different kinds of data distributions, and how to implement them without relying on machine learning libraries.

<img width="811" alt="image" src="https://github.com/user-attachments/assets/cc27aa05-7172-48ce-8cae-97bf5d825cc3" />

---

## 📚 What’s Inside

### 1. **K-Means Clustering**
- Basic formulation with Euclidean and Manhattan distance support
- Custom implementation with KMeans++ initialization
- Examples showing sensitivity to initialization, shape, and scale
- Demonstration of failure cases and how KMeans++ can partially mitigate them

### 2. **Spectral Clustering**
- Explained as a graph-based approach using the Laplacian of a similarity matrix
- Custom implementation using NumPy and eigen decomposition
- Examples where K-Means fails (e.g., rings and moons) but Spectral Clustering succeeds

### 3. **DBSCAN**
- Density-based clustering with noise detection
- Fully implemented from scratch with support for outlier detection
- Examples include noisy ring and wave-shaped clusters where DBSCAN excels

### 4. **Hierarchical Clustering**
- Custom implementation of both bottom-up (agglomerative) and top-down (divisive) strategies
- Dendrogram-based visualization using SciPy
- Demonstration of different clusterings from various cut levels

### 5. **Gaussian Mixture Models (GMM)**
- EM algorithm implemented from scratch
- Comparison with K-Means showing soft clustering and elliptical boundary adaptation
- Fully vectorized for practical usage

---

## 🎨 Visual Demos

The notebook includes several clean and informative visualizations:
- K-Means failure due to poor initialization
- Spectral clustering success on non-convex shapes
- DBSCAN separating noise from real clusters
- Dendrograms for hierarchical clustering
- Elliptical cluster handling via GMMs

<img width="661" alt="image" src="https://github.com/user-attachments/assets/f22cd78e-5d56-4867-9737-dff5662dfb22" />


---

## 🧰 Tools Used

- Python (NumPy, Matplotlib)
- Scikit-learn (only for dataset generation and dendrogram visualization)
- No use of built-in clustering APIs from machine learning libraries
