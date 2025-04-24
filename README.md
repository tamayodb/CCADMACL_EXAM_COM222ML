# CCADMACL Midterm Exam — Clustering Analysis

This notebook serves as the midterm exam for the *Advanced Machine Learning (CCADMACL)* course, focused on applying and comparing three clustering algorithms—**K-Means**, **Agglomerative Clustering**, and **DBSCAN**—across various synthetic datasets.

## Datasets Used
Nine datasets were loaded from external GitHub links, each with varying cluster structures and dimensionalities:

- `face.csv`
- `chrome.csv`
- `lines2.csv`
- `supernova.csv`
- `network.csv`
- `spirals.csv`
- `densedisk.csv`
- `rings.csv`
- `chainlink.csv` (3D dataset)

Each dataset contains feature columns (`x`, `y`, and optionally `z`) and a `color` column indicating ground truth cluster labels.

---

## 📌 Section A: K-Means Clustering

- Removed ground-truth labels (`color`) from datasets.
- Trained K-Means models with pre-defined optimal `k` values.
- Assigned cluster labels and visualized both:
  - Ground truth clusters
  - K-Means predicted clusters
- Visualized `chainlink` in 3D.

---

## 📌 Section B: Agglomerative Clustering

- Applied Agglomerative Clustering using the same `k` values.
- Cluster labels were assigned to each point.
- Visualization mirrored the format in Section A for comparison.

---

## 📌 Section C: DBSCAN Clustering

- Tuned `eps` and `min_samples` per dataset for optimal performance.
- Trained DBSCAN models and labeled clusters, including noise points.
- Again, both correct and predicted clusters were visualized for all datasets.

---

## Objective

The goal of this exam is to:
- Understand and apply unsupervised clustering techniques.
- Evaluate the effectiveness of clustering algorithms in different scenarios.
- Develop insights into how data structure influences clustering performance.

---

## Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- `mpl_toolkits.mplot3d` for 3D visualizations

---

## Link to Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tamayodb/CCADMACL_EXAM_COM222ML/blob/main/Midterm_Exam.ipynb)

---

