# *K-Means-Clustering-from-Scratch*
Implementing and Analyzing K-Means Clustering from Scratch

# Customer Segmentation using K-Means Clustering (From Scratch)

## 📌 Project Overview
This project implements the **K-Means clustering algorithm from scratch using Python** to perform customer segmentation.  
The objective is to understand the internal working of unsupervised learning by manually implementing centroid initialization, distance computation, cluster assignment, centroid updates, and convergence checking.

The custom implementation is then **compared with the scikit-learn implementation** to analyze performance, stability, and the effect of centroid initialization.

---

## 🎯 Objectives
- Implement K-Means clustering from scratch
- Understand centroid movement and convergence
- Segment customers based on behavioral attributes
- Compare custom K-Means with scikit-learn KMeans
- Analyze inertia (Sum of Squared Errors)

---

## 📊 Dataset
**File:** `synthetic_customer_data.csv`

This is a **synthetic dataset** created for learning purposes.

### Features Used
- `age` – Age of the customer  
- `income` – Annual income  
- `experience` – Work experience  
- `spend_score` – Spending behavior score  

---

## ⚙️ Algorithm: K-Means Clustering

### Steps Followed
1. Select number of clusters (K)
2. Randomly initialize centroids
3. Assign each data point to the nearest centroid (Euclidean distance)
4. Update centroids by computing the mean of assigned points
5. Repeat steps 3 and 4 until convergence
6. Visualize the final clusters

---

## 📐 Inertia (Sum of Squared Errors)
Inertia represents the **compactness of clusters** and is calculated as:

