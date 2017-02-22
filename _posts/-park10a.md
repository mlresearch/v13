---
title: Hierarchical Gaussian Process Regression
abstract: We address an approximation method for Gaussian process (GP) regression,
  where we approximate covariance by a block matrix such that diagonal blocks are
  calculated exactly while off-diagonal blocks are approximated. Partitioning input
  data points, we present a two-layer hierarchical model for GP regression, where
  prototypes of clusters in the upper layer are involved for coarse modeling by a
  GP and data points in each cluster in the lower layer are involved for fine modeling
  by an individual GP whose prior mean is given by the corresponding prototype and
  covariance is parameterized by data points in the partition. In this hierarchical
  model, integrating out latent variables in the upper layer leads to a block covariance
  matrix, where diagonal blocks contain similarities between data points in the same
  partition and off-diagonal blocks consist of approximate similarities calculated
  using prototypes. This particular structure of the covariance matrix divides the
  full GP into a pieces of manageable sub-problems whose complexity scales with the
  number of data points in a partition. In addition, our hierarchical GP regression
  (HGPR) is also useful for cases where partitions of data reveal different characteristics.
  Experiments on several benchmark datasets confirm the useful behavior of our method.
pdf: "./park10a/park10a.pdf"
layout: inproceedings
key: park10a
month: 0
firstpage: 95
lastpage: 110
origpdf: http://jmlr.org/proceedings/papers/v13/park10a/park10a.pdf
sections: 
authors:
- given: Sunho
  family: Park
- given: Seungjin
  family: Choi
---
