# Thinkful-Capstone-3
Personal Loan Modeling: Factors and Boundaries
Data from https://www.kaggle.com/teertha/personal-loan-modeling

Less than 10% of the customers accept the personal loans offered to them; how does the company target the correct audience to maximize the acceptance rate? The data includes many fields; we will look at the customer age, experience level, family size, credit card spending level, education level, mortgage status, securities account status, CD account status, and whether or not they opened a credit card at the bank. In the cluster models, which features (factors) are significant enough in predicting the final outcome? What additional information can we use to improve our predictions?

I will use dimensionality reduction methods including PCA, t-SNE, and UMAP and clustering techniques including K-means, hierarchical, DBSCAN, and Gaussian Mixture Models. I will pick the best method and model to recommend.

Based on the clustering results, PCA is the best dimensionality reduction technique between it, t-SNE, and UMAP for this situation. Based on the ARI and silhouette scores, GMM is the best clustering model between it, K-means, hierarchical, and DBSCAN for this situation. On average, those who accepted the personal loans had higher income levels, family sizes, credit card usage levels, education levels, mortgage amounts, and also opened a CD account; can further explore this using supervised learning classification or regression to find the exact breakdown numbers. For the factors found to be non-significant, can test subgroups of the data to see if more trends can be discovered. This is information from one bank. Other financial institutions can pull similar information and use similar models to conduct targeted product marketing.
