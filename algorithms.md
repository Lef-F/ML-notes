# Algorithms

## Joint Graphical Lasso (JGL)

We consider the problem of estimating multiple related Gaussian graphical models from a high-dimensional
data set with observations belonging to distinct classes.
We propose the joint graphical lasso, which borrows strength across the classes in order to estimate multiple graphical models that share certain characteristics, such as the locations or weights of nonzero edges.
Our approach is based upon maximizing a penalized log likelihood.
We employ generalized fused lasso or group lasso penalties, and implement a fast ADMM algorithm to solve the corresponding convex optimization problems.
The performance of the proposed method is illustrated through simulated and real data examples.

Source: [JGL paper](https://arxiv.org/pdf/1111.0324.pdf)

## DBSCAN

Density-based spatial clustering of applications with noise (DBSCAN).
It groups together points that have many nearby neighbors and marks as outliers points that lie alone in low-density regions.
DBSCAN is one of the most common clustering algorithms and also most cited in scientific literature.
DBSCAN can find non-linearly separable clusters.

## Similarity Network Fusion (SNF)

Similarity Network Fusion (SNF) is a new computational method for data integration.
Briefly, SNF combines many different types of measurements (such as mRNA expression data, DNA methylation, miRNA expression and more - clinical data, questionnaires, image data, etc) for a given set of samples (e.g. patients).
SNF first constructs a sample similarity network for each of the data types and then iteratively integrates these networks using a novel network fusion method.
Working in the sample network space allows SNF to avoid dealing with different scale, collection bias and noise in different data types.
Integrating data in a non-linear fashion allows SNF to take advantage of the common as well as complementary information in different data types.

Source> [UC Toronto](http://compbio.cs.toronto.edu/SNF/SNF/Software.html)

## NeuroEvolution of Augmenting Topologies (NEAT)

NEAT is an evolutionary algorithm that creates artificial neural networks.
A population of individual genomes is maintained and each genome contains two sets of genes that describe how to build an artificial neural network:

  * Node genes, each of which specifies a single neuron.
  * Connection genes, each of which specifies a single connection between neurons.

## Order Statistics Local Optimization Method (OSLOM)

OSLOM is the first method capable to detect clusters in networks accounting for edge directions, edge weights, overlapping communities, hierarchies and community dynamics.
It is based on the local optimization of a fitness function expressing the statistical significance of clusters with respect to random fluctuations.
OSLOM can be used alone or as a refinement procedure of partitions/covers delivered by other techniques.
The authors have also implemented sequential algorithms combining OSLOM with other fast techniques, so that the community structure of very large networks can be uncovered.

Source: [OSLOM](http://www.oslom.org/index.html)