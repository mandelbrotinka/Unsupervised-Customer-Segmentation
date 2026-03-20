# Unsupervised-Customer-Segmentation
Implementation of Lloyd's algorithm and K-means++ for data clustering. Applied to synthetic and real-world datasets for pattern recognition.
# Unsupervised Learning: K-means & Customer Segmentation 

### Project Overview
This repository contains a robust implementation of **Lloyd's Algorithm (K-means)** and **K-means++ initialization** for unsupervised clustering. The project focuses on discovering hidden patterns in data without predefined labels—a core task in modern customer analytics.

Developed during the **Master's in Data Science at the University of Vienna**, with a focus on algorithm stability and optimal cluster selection.

### Key Technical Features
* **Lloyd's Algorithm from Scratch:** Manual implementation of the assignment and update steps, including logic for handling empty clusters (resetting to random points).
* **K-means++ Initialization:** Implemented the optimized seeding method to ensure faster convergence and avoid local optima.
* **Optimal K Selection:** Used the **Elbow Method** (K-means objective/inertia analysis) to determine the ideal number of clusters.
* **Robustness Testing:** Evaluated the algorithm on various data distributions (anisotropic, unequal variance, and unevenly sized blobs).

### Tech Stack
* **Language:** Python 3.10+
* **Core Logic:** NumPy (Distance metrics, centroid calculations).
* **Visualization:** Matplotlib (Cluster identity plots and objective curves).
