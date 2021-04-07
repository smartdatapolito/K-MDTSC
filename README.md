K-MDTSC: K-Multi-Dimensional Time-Series Clustering Algorithm
=========================================

This repository contains the code to run the clustering algorithm K-MDTSC (K-Multi-Dimensional Time-Series Clustering) and reproduce the results presented in the paper "K-MDTSC: K-Multi-Dimensional Time-Series Clustering" submitted to Electronics, MDPI.
K-MDTSC is a novel clustering algorithm based on K-means, specifically designed to deal with multi-dimensional time-series. 

In details, the repository contains:
- Cluster_Synthetic.ipynb is a Jupyter notebook where we present K-MDTSC reproduces the comparison between k-Shape[1] and K-MDTSC running the stability analysis with a synthetic dataset. 
- Analyse_Synthetic.ipynb is a Jupyter notebook used to reproduce the paper's plots regarding the stability analysis with a synthetic dataset.
- result contains the pickles having the datasets generated for the stability analysis and the clustering results. Notice that creating a new dataset or running the code multiple times may give slightly different performance due to the k-Means characteristics.
- fig presents the figures reported in the paper. 
