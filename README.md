# Customer Segmentation using RFM Analysis and Machine Learning

## Project Overview

This project segments customers using:

- RFM Analysis (Recency, Frequency, Monetary)
- K-Means Clustering
- PCA Visualization
- Isolation Forest for Anomaly Detection

## Steps Performed

1. Data Cleaning
2. Feature Engineering (RFM)
3. Feature Scaling
4. Elbow Method for Optimal K
5. K-Means Clustering
6. PCA Visualization
7. Isolation Forest
8. Cluster Analysis

## Customer Segments

| Cluster | Segment |
|--------|--------|
| 0 | Lost Customers |
| 1 | Regular Customers  |
| 2 | VIP Customers  |
| 3 | Whale Customers  |

---

## PCA Visualization

![PCA Visualization](images/pca_visualization.png)

The PCA plot reduces the 3-dimensional RFM features into 2 dimensions to visualize customer segments.

---

## Anomaly Detection

![Anomaly Detection](images/anomaly_detection.png)

Isolation Forest identifies unusual customers whose purchasing behavior is significantly different from the majority.

---

## Business Insights

- Lost Customers → Re-engagement campaigns.
- Regular Customers → Loyalty disocunts.
- VIP Customers → Premium offers.
- Whale Customers → Dedicated account management.

## Technologies Used

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook
