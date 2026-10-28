# Customer Segmentation Using K-Means Clustering

## Project Overview

This project applies unsupervised machine learning to group customers based on Instagram engagement and spending behavior.

The objective is to identify distinct customer segments that could support more targeted marketing strategies and better understanding of customer behavior.

## Dataset

**Instagram visits clustering.csv**

The dataset includes:

- User ID: Unique customer identifier
- Instagram visit score: Customer engagement measurement
- Spending rank (0 to 100): Customer spending behavior

## Tools & Libraries

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn

## Methodology

1. **Data Exploration:** Loaded and inspected the dataset.
2. **Feature Selection:** Excluded User ID because it does not represent customer behavior.
3. **Data Visualization:** Explored relationships between Instagram engagement and spending.
4. **Elbow Method:** Tested different cluster counts using inertia.
5. **Silhouette Analysis:** Evaluated cluster separation and cohesion.
6. **K-Means Modeling:** Developed a final K-Means model using four clusters.
7. **Cluster Profiling:** Analyzed the characteristics of each customer segment.

## Key Findings

Four customer segments were identified:

| Cluster | Customer Behavior |
|---|---|
| 0 | High Instagram engagement, low spending |
| 1 | Low Instagram engagement, high spending |
| 2 | High Instagram engagement, high spending |
| 3 | Low Instagram engagement, low spending |

## Business Applications

These segments could help businesses:

- Identify highly engaged customers with conversion potential.
- Develop targeted campaigns for low-engagement, high-spending customers.
- Recognize high-value customers for retention strategies.
- Tailor marketing approaches to different customer behaviors.

## Learning Outcomes

- Understanding unsupervised learning
- Selecting an appropriate number of clusters
- Using the Elbow Method and Silhouette Scores
- Training and interpreting K-Means models
- Translating clustering results into potential business insights

## Future Improvements

- Explore additional customer behavior variables.
- Compare K-Means with other clustering methods.
- Validate segment stability on new data.
