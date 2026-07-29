# AI-ML Assignment 7: Customer Segmentation using K-Means and PCA

## Objective
Segment shopping mall customers into distinct groups based on income, age, and spending behavior using K-Means clustering, and visualize the clusters using Principal Component Analysis (PCA).

## Dataset Link
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Libraries Used
*   pandas
*   numpy
*   matplotlib
*   seaborn
*   scikit-learn

## Methodology
1. **Data Preprocessing:** Handled missing values, dropped non-informative columns (`CustomerID`), encoded `Gender`, and standardized features using `StandardScaler`.
2. **Optimal K Identification:** Applied the Elbow Method (WCSS) to select $K = 5$.
3. **Clustering & PCA:** Trained `KMeans(n_clusters=5)` and compressed the dataset to 2 principal components using `PCA`.

## Results
- **Optimal Clusters:** 5 clear customer personas identified.
- **PCA Dimensionality Reduction:** Compressed 4 scaled features into 2 2D projection components for easy visual evaluation.

## Conclusion
Customer segmentation enables targeted marketing campaigns that maximize ROI. While K-Means requires pre-defining $K$, PCA simplifies high-dimensional analysis for decision-makers.