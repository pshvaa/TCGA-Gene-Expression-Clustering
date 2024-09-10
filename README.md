# TCGA-Gene-Expression-Clustering

This repository contains an analysis of gene expression data obtained from The Cancer Genome Atlas (TCGA) Pan-Cancer analysis project.

## Dataset Overview

The dataset contains **881 samples** (rows), each representing a patient with one of **five distinct cancer subtypes**. Each sample includes gene expression values for **20,531 genes** (columns). The dataset is sourced from the **UC Irvine Machine Learning Repository**.

## Objective

The objective of this project is to use **KMeans clustering** to identify distinct cancer subtypes based on gene expression data. By applying clustering techniques, we aim to explore how well unsupervised learning can distinguish between different cancer subtypes.

## Methodology

1. **Data Preprocessing**: 
   - Normalization and scaling of the gene expression values.
   
2. **KMeans Clustering**: 
   - Applied KMeans to identify clusters representing the five distinct cancer subtypes.
   
3. **Evaluation**: 
   - Evaluated the performance of the clustering model using relevant metrics.

## Dataset Source

The dataset is available from the **[UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)** and includes gene expression data collected by The Cancer Genome Atlas (TCGA) Pan-Cancer analysis project investigators.

## Results

The analysis reveals distinct clusters that correspond to the different cancer subtypes, showcasing the potential of unsupervised machine learning for biological data analysis.

## Requirements

- Python 3.x
- Pandas
- NumPy
- scikit-learn
- Matplotlib

