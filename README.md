# clustering-msnbc
Clustering of msnbc web data

In this project we group user of web portal msnbc.com analyzing anonymous data of visited page categories.

Techniques and methods used:
- dimensionality reduction methods: t-SNE and UMAP
- clustering methods: MiniBatchKMeans, DBSCAN, HDBSCAN

The challanges:
- finding the proper data representation
- size of data set (approx. 1M records) - lacks of resources
- finding the proper dimenionality reduction method and its optimal parameteres
- findig optimal clustering method (due to size of data and its character)
- understandable representation of results

To do:
- implement workflow unig RAPIDS Nvidia library on GPU instance to tune up hyperparameters of UMAP algorithm
