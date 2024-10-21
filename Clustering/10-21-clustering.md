
I = *inertia* (coincides with variance in the statistical sense) corresponds to the weighted sum of distances (mass * Δx) with respect to the centroid of the whole dataset.

W = variance / inertia within the cluster. Measures the lack of heterogeneity within a cluster

B = Intertia between clusters. Variance of the clusters with respect to the global centroid. Measures the distinguishability between clusters.

The good clustering will aim to maximize B while minimizing W.
W + B = I (constant)


El K-means pot fallar més que una escopeta de fira, especialment si els "clusters reals" no tenen una estructura globular. Els profes volen que saltem a hierarchical clustering o altres mètodes directament.

R és molt millor que python per fer clustering amb categorical data. 