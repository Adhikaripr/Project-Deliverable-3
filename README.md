# Project-Deliverable-3

## Comparative Clustering Analysis: K-Means versus K-Medoids Applied to the Wine Dataset
## Objective
This laboratory exercise explored clustering methodologies using the Wine Dataset from sklearn. The primary aim was to implement and contrast two clustering algorithms—K-Means and K-Medoids—to assess their effectiveness in grouping wine samples according to chemical characteristics. Algorithm performance was measured through the Silhouette Score and Adjusted Rand Index (ARI) to identify which approach generated more interpretable and precise clusters. Visual representations were created to examine the geometric properties and spatial distribution of clusters produced by each technique.
Principal Findings

## K-Means demonstrated superior cluster cohesion and separation relative to K-Medoids.

#Silhouette Score: K-Means (0.28) exceeded K-Medoids (0.27)
#Adjusted Rand Index: K-Means (0.90) surpassed K-Medoids (0.74)
These results indicate that K-Means clustering exhibited stronger correspondence with the true wine classifications.


K-Means achieved better results because the dataset features compact and well-differentiated groupings. K-Medoids, despite its enhanced resistance to anomalous data points, failed to establish distinct cluster boundaries in this scenario.
PCA-based visualizations demonstrated that K-Means generated spherical cluster formations, while K-Medoids created more irregular geometric patterns.

## Implementation Challenges and Strategic Decisions

#Feature Standardization: Applying z-score normalization proved crucial to ensure equitable contribution from each attribute during the clustering process.
#Medoid Initialization: Selecting initial medoids for K-Medoids presented difficulties. We employed manual selection, though more sophisticated initialization strategies could enhance clustering outcomes.
#Performance Assessment: Evaluating cluster quality necessitated both numerical metrics and visual analysis.

#Quantitative measures: Silhouette Score and ARI enabled objective algorithm comparison.
#Qualitative assessment: PCA visualizations facilitated examination of cluster distinctiveness and structural characteristics.
