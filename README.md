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
`Inertia = Σ (distance between each point and its centroid)²`

Lower inertia indicates better clustering.

---

## 🔬 Comparison: Custom vs Scikit-Learn Implementation

| Aspect | Custom Implementation | Scikit-Learn |
|------|----------------------|--------------|
| Control | Full control over each step | Abstracted |
| Speed | Slower | Faster |
| Learning Value | Very high | Moderate |
| Stability | Depends on initialization | Uses optimized methods |

---

## 📈 Visualization
Clusters are visualized using:
- X-axis: Income  
- Y-axis: Spending Score  
- Centroids marked using `X`

---

## 🛠 Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📊 Result Analysis

## Performance:
The scikit-learn implementation converges faster due to optimized vectorized operations, whereas the custom implementation is slower because it uses explicit loops.

**Stability:**
The custom implementation is more sensitive to centroid initialization. Different random seeds can lead to different clustering outcomes. Scikit-learn mitigates this by using smarter initialization techniques.

**Interpretation:**
Both implementations produced similar cluster structures, confirming the correctness of the custom algorithm. The slight difference in inertia values highlights the impact of initialization and numerical optimization.

**Impact of Initialization:**
Random centroid initialization can affect final clusters. Poor initial centroids may lead to higher inertia or suboptimal segmentation. This reinforces the importance of initialization strategies in K-Means.

--- 

## 📐 Inertia (Sum of Squared Errors)

Inertia measures how well the data points are clustered around their respective centroids.  
It is calculated as the **sum of squared Euclidean distances** between each data point and its assigned centroid.

### Final Inertia Values

- **Custom K-Means Implementation:**  
Final Inertia (Custom K-Means): `11137751639.519419`

- **Scikit-Learn KMeans Implementation:**
Final Inertia (Scikit-Learn KMeans): `11119014323.31233`

### Observation
- The scikit-learn implementation produces slightly lower inertia due to optimized centroid initialization and numerical computation.  
- The similarity in inertia values confirms the correctness of the custom K-Means implementation.

---

**✅ Conclusion**
- This project provides a deep understanding of K-Means clustering by building it from scratch and validating results using scikit-learn.  
- It strengthens core machine learning fundamentals and prepares the learner for real-world ML applications.

--- 
