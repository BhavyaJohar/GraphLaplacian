# Social Media Clustering
## Description
This project involves performing spectral clustering on a graph dataset to identify distinct clusters of nodes based on their connectivity patterns. The steps involved include computing the degree matrix, adjacency matrix, graph Laplacian, and performing spectral clustering to assign nodes to different clusters. The dataset used for this assignment contains information about the connections between users on a social media platform. Each row in the dataset represents a connection (edge) between two users, indicated by their unique user IDs.

## Contents

Import and Load Data: 
- The initial step involves importing necessary libraries and loading the dataset.

Degree Matrix: 
- Calculation of the degree matrix, which is a diagonal matrix representing the number of edges connected to each node.

Adjacency Matrix: 
- Construction of the adjacency matrix, which represents the connections between nodes in the graph.

Graph Laplacian Matrix: 
- Computation of the graph Laplacian, which is used in spectral clustering to understand the structure of the graph.

Spectral Clustering: 
- Implementation of spectral clustering to group nodes into clusters based on the eigenvalues and eigenvectors of the graph Laplacian.

Cluster Assignment: 
- The resulting cluster assignments for each node in the graph.

## Cluster Analysis:

Dominant Cluster: 
 - Analysis of the largest cluster, which includes almost all users, indicating similar connectivity patterns or sparse connections.
Minor Clusters:
 - Identification and analysis of smaller clusters, indicating tightly knit sub-communities with unique connection patterns.
## Analysis and Insights
### Cluster Assignment:
Dominant Cluster (0): 
- Most users are grouped into this cluster, indicating uniform connectivity or sparse connections.
Minor Clusters (1, 2, 3, 4):
- Small groups of users forming distinct sub-communities within the network.
### Possible Reasons and Implications:
Graph Structure: 
- A large component with several smaller, tightly connected components can lead to this clustering outcome.
Parameter Settings:
- The choice of the number of clusters and eigenvectors significantly impacts the clustering results.
Data Characteristics:
- Uniform connectivity patterns across users can result in most users being placed into a single cluster.
