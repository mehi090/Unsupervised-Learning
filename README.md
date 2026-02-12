# Iris Species Clustering using K-Means and Hierarchical Clustering

## Project Overview

This project demonstrates the implementation of unsupervised machine learning algorithms using the classic Iris dataset. The objective is to cluster iris flowers into groups based on their morphological characteristics and evaluate how well the clustering aligns with the actual species.

The project applies K-Means and Hierarchical Clustering techniques to analyze patterns within the dataset and compare the behavior of both algorithms.

## Dataset Description

The dataset contains 150 observations from three iris species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each observation includes the following features:

- Id
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm
- Species

The Iris dataset was introduced by Ronald A. Fisher in 1936 in the paper "The Use of Multiple Measurements in Taxonomic Problems" and is widely used for pattern recognition and machine learning tasks.

## Project Objectives

- Perform clustering using K-Means
- Perform clustering using Hierarchical (Agglomerative) Clustering
- Determine the optimal number of clusters
- Visualize cluster distribution
- Compare clustering structures
- Analyze clustering performance

## Methodology

### Data Preprocessing
- Removed unnecessary columns
- Applied feature scaling
- Prepared data for clustering

### K-Means Clustering
- Used the Elbow Method to determine optimal number of clusters
- Trained K-Means model
- Visualized cluster assignments

### Hierarchical Clustering
- Generated dendrogram
- Applied Agglomerative Clustering
- Compared cluster structure with K-Means results

## Results and Insights

- Petal length and petal width are the most influential features for clustering.
- Setosa species forms a clearly separable cluster.
- Versicolor and Virginica show partial overlap.
- Both algorithms produce similar clustering patterns, though hierarchical clustering provides better structural interpretation.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy



## Skills Demonstrated

- Data preprocessing
- Feature scaling
- Unsupervised machine learning
- Model comparison
- Data visualization
- Analytical thinking

## Future Improvements

- Apply PCA for dimensionality reduction
- Evaluate clustering with silhouette score
- Compare results with DBSCAN
- Convert into Jupyter Notebook for better presentation
- Build interactive visualization using Streamlit
