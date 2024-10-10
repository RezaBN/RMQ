# Range Minimum Queries (RMQ) Solutions

## What is the RMQ problem?
The ***RMQ*** problem asks for the minimum value within a given subarray of a larger array. It's a fundamental problem in data structures with applications in various domains like text editing, dynamic programming, and bioinformatics.

This repository explores six different approaches to solving the *RMQ* problem, analyzing their performance based on the following metrics::

* ***Querying and Preprocessing Completed Time (Run Time):*** Measures the total time taken to preprocess the data and execute queries.
* ***Memory Usage During Preprocessing and Querying:*** Tracks the current memory usage and peak memory usage during both preprocessing and query operations.
* ***Time Complexity of Preprocessing and Querying:*** Analyzes the theoretical time complexity of the algorithms involved in preprocessing and querying.

The implemented approaches in RMQ.ipynb include:
* ***Naive:*** A brute-force approach that iterates through the entire subarray to find the minimum.
* ***Precomputation-based:*** Precomputes the minimum values for all possible subarrays, allowing for constant-time queries.
* ***Block Decomposition:*** Divides the array into blocks and precomputes the minimum for each block, improving query efficiency for large arrays.
* ***Sparse Table:*** A data structure that uses dynamic programming to efficiently compute and store minimum values for subarrays of various sizes.
* ***Hybrid Solutions*** (Two approaches): Combine elements of block decomposition and sparse table to achieve a balance of preprocessing time and query efficiency.
-----------------------------------------------------
All approaches are implemented on the same initial **array with a size of 2^16**, and their performance is evaluated on both this array and a larger array with **a size of 2^17**. Each approach is implemented in a separate code cell for clarity and comparison.
------------------------------------------------------

## Getting Started:
1. Clone this repository.
2. Install any necessary dependencies (usually Jupyter and its libraries).
3. Open RMQ.ipynb in a Jupyter Notebook environment.
4. Run the code cells to explore each approach and visualize their behavior.


