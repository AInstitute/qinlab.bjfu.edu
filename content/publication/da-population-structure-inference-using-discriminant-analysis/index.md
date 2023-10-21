---
title: "DA: Population structure inference using discriminant analysis"
publication_types:
  - "0"
authors:
  - admin
  - Thomas Ryan Lock
  - Robert L. Kallenbach
doi: 10.1111/2041-210X.13748
publication: Methods in Ecology and Evolution
publication_short: Methods Ecol. Evol.
abstract: >2
  
   1. Genetic variations in a species across geographic areas typically exhibit spatial clines. There is increasing interest in inferring population genetic structure to understand the patterns of genetic variation and the evolution of a species.
   2. Here, we present the da package and propose to infer population structure using discriminant analysis (DA). We incorporate five supervised learning approaches (DAPC, LDAKPC, LFDA, LFDAKPC and KLFDA) into da package within the same DA family, but with different linear and nonlinear properties.
  3 . We tested the performance and properties of these five approaches for population structure inference using both simulated and empirical data. Results showed that these five approaches preserved the same global genetic structure under each genetic scenario. Notably, genetic features produced from KLFDA and LFDA had higher correlations with urn:x-wiley:2041210X:media:mee313748:mee313748-math-0001 under isolation-by-distance model and higher discriminatory power in population structure identification, with KLFDA achieving the best performance. The applications to empirical data indicated that all these methods could intuitively capture the continuous genetic gradients while LFDA and KLFDA could discriminate nuanced population structures that the other approaches cannot.

  4. These DA methods can be applied to other statistical inferences in genetics and beyond. The da package is available at https://cran.r-project.org/web/packages/DA/index.html. We recommend users choosing these approaches appropriately depending on their scientific questions and target data.
draft: false
featured: false
image:
  filename: mee313748-fig-0003-m.jpg
  focal_point: Smart
  preview_only: false
  caption: The Mantel's r between the population genetic fixation
    urn:x-wiley:2041210X:media:mee313748:mee313748-math-0043 and the Euclidean
    distance of the populations projected by five methods. The p-values of five
    approaches are all <1e-4
date: 2022-08-13T13:43:54.617Z
---
