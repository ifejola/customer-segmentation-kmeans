# customer-segmentation-kmeans
Customer segmentation using K-Means clustering with elbow method and silhouette score for optimal cluster selection
# Customer Segmentation Using K-Means Clustering

## Overview
This project applies K-Means clustering to segment users based on behavioral data, specifically Instagram engagement and spending patterns.

The goal is to identify distinct customer groups that can support targeted marketing strategies and better understand user behavior.

---

## Dataset
The dataset contains 2,600 user records with the following features:
- Instagram Visit Score
- Spending Rank (0–100)

These features were used to identify natural groupings in user behavior.

---

## Tools & Libraries
- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Methodology

### 1. Data Exploration
- Loaded and explored dataset using pandas
- Checked data structure and distributions
- Visualized relationships using scatter plots and histograms

### 2. Feature Selection
- Selected relevant features:
  - Instagram Visit Score
  - Spending Rank

### 3. Clustering
- Applied K-Means clustering using scikit-learn
- Tested multiple cluster values (k = 2 to 10)

### 4. Model Evaluation
- Used **Elbow Method** to analyze inertia
- Used **Silhouette Score** to validate cluster quality
- Determined optimal number of clusters: **k = 4**

### 5. Final Model
- Built final K-Means model with k = 4
- Assigned cluster labels to each user

---

## Results & Insights
- Identified **4 distinct customer segments**
- Segments show varying levels of engagement and spending behavior
- Some users show high engagement but low spending (growth opportunity)
- Others show high spending, indicating strong customer value

---

## Visualizations
- Raw data distribution (scatter plot)
- Feature distributions (histograms)
- Elbow curve for optimal cluster selection
- Silhouette score curve
- Cluster comparison visuals

---

## Conclusion
K-Means clustering effectively grouped users into meaningful segments, providing insights that can be used for targeted marketing and strategic decision-making.

---

## Future Improvements
- Include additional behavioral features
- Apply scaling/normalization for improved clustering
- Compare with other clustering algorithms (DBSCAN, Hierarchical)
- Deploy model for real-time segmentation
