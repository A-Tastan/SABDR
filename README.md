# SABDR
SPARSITY-AWARE BLOCK DIAGONAL REPRESENTATION FOR SUBSPACE CLUSTERING

A block diagonally structured affinity matrix is an informative prior for subspace clustering which embeds the data points in a union of low-dimensional 
subspaces. Structuring a block diagonal matrix can be challenging due to the determination of an appropriate sparsity level, especially when outliers and 
heavy-tailed noise obscure the underlying subspaces. We propose a new sparsity-aware block diagonal representation (SABDR) method that robustly estimates
the appropriate sparsity level by leveraging upon the geometrical analysis of the low-dimensional structure in spectral clustering. Specifically, we derive
the Euclidean distance between the embeddings of different clusters to develop a computationally efficient density-based clustering algorithm. In this way,
the sparsity parameter selection problem is re-formulated as a robust approximation of target between-clusters distances. Comprehensive experiments using 
real-world data demonstrate the effectiveness of SABDR in different subspace clustering applications.

For details, see:

[1] A. Tastan, M. Muma, E. Ollila and A. M. Zoubir, "Sparsity-Aware Block Diagonal Representation for Subspace Clustering," in Proc. Int. Conf. Acoust. 
Speech Signal Process.(submitted), 2023.

The codes will be available after the acceptence.
