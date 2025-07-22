# Multi-structural-Hypergraph-Joint-Embedding-for-Dimensionality-Reduction-in-Rotor-Fault-Diagnosis.
Traditional methods of constructing graph models based on label information to drive first-order relationships struggle to adaptively mine higher-order geometric structures and global features among samples, limiting the expressive power of the resulting graph models. To address this issue, this study proposes Joint Embedding for Multi-structural Hypergraph (JEMSH) based Dimensionality Reduction in Rotor Fault Diagnosis. First, the algorithm constructs intra-class and inter-class hypergraphs using Euclidean distance and local geometric prior information. It then adaptively selects neighboring domains via sparse representation to build intra-class sparse hypergraphs and inter-class sparse hypergraphs. Finally, a multi-structural hypergraph objective function is formulated using a weighted difference criterion to enhance intra-class sample compactness and maximize inter-class sample separation. This dual-structural fusion strategy captures global subspace relationships and local geometric features, enabling extraction of more discriminative low-dimensional representations.
# Configuration environment software matlab-2020a
# In JEMSH program 
1. A is the original dataset of time domain, frequency domain and time-frequency domain feature extraction (each row represents one sample and each column represents one feature) 
2. XL is the number of training samples for each class of states 
3. CS is the number of test samples for each class of states 
4. LBS stands for the type of fault class 
5. tT, LLL stands for the number of intra-class sparse, inter-class sparse 
6. eigvector stands for the target downscaling matrix for solving 
7. ZQL refers to the classification recognition accuracy by KNN classifier 
8. When running the JEMSH program program, you must first add the JEMSH sub-code package in the matlab software path
