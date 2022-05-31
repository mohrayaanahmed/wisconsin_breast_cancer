# wisconsin_breast_cancer
Exploratory data analysis of the wisconsin breast cancer dataset and clustering

SOURCE OF THE DATASET: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

1. Introductory analyses: statistical descriptions of various attributes for benign and malignant data.
2. Histogram threshold: A histogram of all the attributes and a threshold line contrasting malignant and benign data.
3. knn: k-nearest neighbour model used for ML clustering of the data.
4. pca: Principal component analysis done for dimensionality reduction of the data. Eigen-values were defined and then PCA were created in accordance to the eigen-values.
5. Linear discriminant: Fisher's linear discriminant model used on the dataset for prediction of clustering of benign and malignant data.
6. k-means: k with the values of (2,3 and 5) clusters created with centroids and respective David Bouldin index. WHAT IS DAVID BOULDIN INDEX? (https://python-bloggers.com/2021/06/davies-bouldin-index-for-k-means-clustering-evaluation-in-python/)
7. Relative information gain: The code consists of comments that describe the calculation of RIG.
8. Purity: Purity is an evaluation metric of clustering like k-means. It basically describes the accuracy of a cluster. READ MORE (https://towardsdatascience.com/evaluation-metrics-for-clustering-models-5dde821dd6cd?gi=716ae146da5c#:~:text=Purity%20is%20quite%20simple%20to,number%20of%20total%20data%20points.&text=Each%20cluster%20is%20assigned%20with%20the%20most%20frequent%20class%20label.) 
