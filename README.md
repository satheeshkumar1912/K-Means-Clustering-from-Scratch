# *K-Means-Clustering-from-Scratch*
Implementing and Analyzing K-Means Clustering from Scratch

# Customer Segmentation using K-Means Clustering

## Problem Statement
The objective of this project is to segment customers based on their demographic
and spending behavior using the K-Means clustering algorithm. The goal is to
identify distinct customer groups that can help businesses make better
data-driven decisions.

## Dataset
A synthetic dataset containing 200 customer records was used in this project.
The dataset includes the following features:

- Age
- Annual Income
- Years of Experience
- Spending Score

An additional column indicating purchase behavior is used only for interpretation
and not for clustering.

## Approach
1. Load and understand the dataset
2. Select relevant features for clustering
3. Visualize and explore data patterns
4. Choose the number of clusters (K = 4)
5. Initialize centroids
6. Assign data points to nearest centroids
7. Update centroids using mean values
8. Repeat until convergence
9. Interpret and evaluate clusters

## Algorithm Used
- K-Means Clustering (Unsupervised Machine Learning)

## Results
The algorithm successfully grouped customers into four meaningful clusters.
Each cluster represents a different customer segment based on income,
experience, and spending behavior.

## Business Insights
- Different marketing strategies can be designed for each customer group
- High spending clusters can be targeted with premium offers
- Low engagement clusters can be nurtured with promotions

## Conclusion
This project demonstrates how K-Means clustering can be used to discover
hidden patterns in customer data and support business decision-making.




1️⃣ README.md (EXACTLY what you can paste)
📌 Project Title

Customer Segmentation using K-Means Clustering (From Scratch)

📖 Project Description

This project demonstrates how K-Means clustering works internally by implementing the algorithm from scratch using Python, without relying on machine learning libraries.

The goal is to segment customers based on their age, income, experience, and spending score, and understand how unsupervised learning can discover hidden patterns in data.

🎯 Objectives

Understand K-Means clustering intuitively

Learn centroid initialization, distance calculation, and convergence

Segment customers into meaningful groups

Visualize clusters for business interpretation

📊 Dataset

synthetic_customer_data.csv

Features used:

age – Customer age

income – Annual income

experience – Work experience

spend_score – Spending behavior indicator

The dataset is synthetic and created only for learning purposes.

⚙️ Algorithm Used

K-Means Clustering (From Scratch)

Steps:

Choose number of clusters (K)

Initialize centroids randomly

Assign each data point to nearest centroid

Update centroids using mean of assigned points

Repeat until convergence

📈 Visualization

Clusters are visualized using:

X-axis: Income

Y-axis: Spending Score

Centroids shown using X marker

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

✅ Outcome

Customers successfully grouped into 4 clusters

Clear separation based on spending behavior

Practical understanding of unsupervised learning

📌 Conclusion

This project builds strong fundamentals in clustering and prepares the learner to use advanced ML libraries like scikit-learn confidently.
