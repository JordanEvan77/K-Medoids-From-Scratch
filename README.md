# K-Medoids-From-Scratch
Creating an Unsupervised learning algorithm from scratch and then testing it on the transfusion blood data set.
This function is designed to take in a distance matrix and do the following:
:param D: an NxN distance matrix. In other words, D is a two dimensional list and D[i][j] is the
    distance between data points i and j. D should be symmetric, and D[i][i] should be zero for all
    values of i. For all i and j, if i and j are different, then D[i][j]>0.
    :param K:the number of clusters and should be smaller than the number of data points (i.e., K<N).
    :param maxIter:the maximum number of times that your algorithm iterates.
    :return: 2 Types of clusters. Firstly, A list of size N (number of data points) that indicates
    the cluster ID of each data point. Cluster IDs start at 0. Hence, if Clusters[5] is 2, it means
    that data point #5 belongs to cluster #2. Secondly, A list of size K that for each cluster,
    includes the ID of the data point which is selected as the cluster center
    
I utilize several setws of nested lists and spatial manipulation to create this system, demonstrating my ability to understand algorithms and reconstruct them.
