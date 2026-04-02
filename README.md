# DeepLearning_Project5

This project contains the completed notebook for **Unsupervised and Semi-Supervised Learning** using the **CIFAR-10** dataset.

## File

- `Project5_Unsupervised_SemiSupervised.ipynb`: Main notebook for the project

## What is implemented

The notebook is organized into five parts:

1. **Conceptual Questions**
   - Difference between supervised and unsupervised learning
   - Definition of semi-supervised learning
   - Importance of representation learning

2. **Unsupervised Learning**
   - CIFAR-10 data loading and preprocessing
   - Feature standardization
   - Dimensionality reduction using **PCA**
   - Clustering using **K-Means**
   - Cluster quality evaluation with metrics such as:
     - Adjusted Rand Index (ARI)
     - Normalized Mutual Information (NMI)
     - Majority-vote cluster accuracy
   - Cluster visualization and sample inspection

3. **Visualization**
   - 2D visualization of learned features using **t-SNE**
   - Comparison of true class structure and discovered clusters

4. **Semi-Supervised Learning**
   - Simulation with only **10% labeled data**
   - Baseline supervised model on the labeled subset
   - **Pseudo-labeling** for unlabeled samples
   - Comparison with a fully supervised reference model

5. **Reflection**
   - Advantages of semi-supervised learning
   - Practical scenarios where these methods are useful

## Main methods used

- `PCA` for dimensionality reduction
- `K-Means` for clustering
- `t-SNE` for visualization
- `Logistic Regression` for supervised and semi-supervised classification

## Required libraries

To run the notebook, install the following Python packages:

- `numpy`
- `matplotlib`
- `scikit-learn`
- `torchvision`

If needed, you can install them with:

```bash
pip install numpy matplotlib scikit-learn torchvision
```

## Notes

- The project uses **CIFAR-10** as requested.
- The code includes explanatory **English comments** to make the implementation easier to study.
- Balanced subsets are used in the notebook to keep the runtime reasonable while preserving all classes.
