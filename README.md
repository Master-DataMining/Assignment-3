# Assignment-3

# Goal

Implement ANN algorithm on Airbnb New York dataset and find the hotels that are most similar to each other.

# Data Cleaning

1. Removed all NULL values
2. Dropping columns that do not contribute in training the model
3. Renaming the columns to have more apt and meaningful names
4. Dropping the rows where the availablity for that property is 0.

# Data Visualization

After data cleaning, visualizing the datset to have a better understanding of the dataset and to check if the data is more clear.

# ANN (Approximate Nearest Neighbor) Algorithms

It is a techniques that speed up the search by preprocessing the data into an efficient index.

1. Vector Transformation
2. Vector Encoding
3. None Exhaustive Search Component

# LSH (Locality Sensitive Hashing)

LSH-based algorithms are one of the most common strategies when it comes to ANN. 

They construct a hash table as their data structure by mapping points that are nearby into the same bucket.

A larger value will give more accurate results, but larger indexes.

# Exhaustive Search using Faiss

Exhaustic search using Fiass Library.

Faiss is a library used for making the similarity search more efficient and clustering of dense vectors.

The algorithms can search in sets of vectors of any size.

Exhaustive Search is the only available method for guaranteed retrieval of the exact nearest neighbor is exhaustive search.

# Product Quantization

Quantization-based algorithms are one of the most common strategies when it comes to ANN.

Reduces the dataset size from linear to quantizer by defining a function that encodes the dataset into a compact approximated representation.


# Approximate Nearest Neighbors Using HNSW (Hierarchical Navigable Small World Graphs)

Created an index class by defining NMSLIB index class with the Airbnb datasets

Installed the nmslib library which is cross platform similarity search library

# Trees and Graphs

Implemeted the Trees and Graphs using Annoy library which construct index using the trees or forests.

Tree-based algorithms are one of the most common strategies when it comes to ANN. 

They construct forests or teh collection of trees as their data structure by splitting the dataset into subsets.

Accuracy performance tradeoff is controlled by :

1. Number of trees — A larger value will give more accurate results, but larger indexes.
2. Search K — the number of binary trees we search for each point. The arger value will give more accurate results, but will take a longer time to return.
