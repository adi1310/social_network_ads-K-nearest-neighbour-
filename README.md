# K Nearest Neighbour
k-NN is a type of instance-based learning, or lazy learning, where the function is only approximated locally and all computation 
is deferred until classification. The k-NN algorithm is among the simplest of all machine learning algorithms. 

In the classification phase, k is a user-defined constant, and an unlabeled vector (a query or test point) is classified by 
assigning the label which is most frequent among the k training samples nearest to that query point.

A commonly used distance metric for continuous variables is Euclidean distance. For discrete variables, such as for text 
classification, another metric can be used, such as the overlap metric (or Hamming distance). In the context of gene expression 
microarray data, for example, k-NN has been employed with correlation coefficients, such as Pearson and Spearman, as a metric.[3] 
Often, the classification accuracy of k-NN can be improved significantly if the distance metric is learned with specialized 
algorithms such as Large Margin Nearest Neighbor or Neighbourhood components analysis. 
