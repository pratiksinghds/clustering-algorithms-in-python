# Unsupervised Machine Learning: Comparative Clustering Analysis

[![Python Version](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2%2B-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Lab-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An in-depth, hands-on repository implementing and evaluating the three foundational paradigms of unsupervised clustering: **Centroid-Based (K-Means)**, **Connectivity-Based (Agglomerative Hierarchical)**, and **Density-Based (DBSCAN)**.

---

## 📑 Table of Contents
- [Project Architecture](#-project-architecture)
- [Algorithmic Breakdown & Methodology](#-algorithmic-breakdown--methodology)
  - [1. K-Means Clustering](#1-k-means-clustering)
  - [2. Hierarchical Agglomerative Clustering](#2-hierarchical-agglomerative-clustering)
  - [3. DBSCAN](#3-dbscan)
- [Comparative Matrix](#-comparative-matrix)
- [Evaluation Metrics Guide](#-evaluation-metrics-guide)
- [Getting Started](#-getting-started)
- [Dependencies](#-dependencies)
- [License](#-license)

---

## 📁 Project Architecture

```text
├── K Means Clustering.ipynb        # WCSS optimization, Elbow method, Silhouette analysis
├── Hierarichal Clustering.ipynb    # Dendrogram visualization, linkage matrix experiments
├── DBSCAN Clustering.ipynb         # k-NN distance graph, epsilon tuning, noise classification
├── requirements.txt               # Pinned project dependencies
└── README.md                       # Repository documentation
