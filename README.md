# Unsuperviesed Learning

In this repo we conduct comparative analysis of different unsupervised learning methods for Anomaly Detection, Density Estimation and Clustering. We applied the methods on the MoCap Hand Postures Data Set and the pulsar radio emission HTRU2 Data Set . The data sets are much different, still we find common trends, UMAP for dimension reduction and Non-linear clustering methods are significantly better in finding high quality clusters. In both datasets GMM learned cluster that highly correlated with the real classes of the datasets. Our conclusion is that both data sets contain some non-linear differences between classes but within the same class features are distributed normally.

[Read the full PDF report here.](https://github.com/elronbandel/unsupervised-learning/blob/main/unsupervised-learning.pdf?raw=true)

![clusters](https://github.com/elronbandel/unsupervised-learning/blob/main/figure7.png?raw=true)