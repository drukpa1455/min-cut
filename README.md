# Deterministic Near-Linear Time Minimum Cut in Weighted Graphs
Proceedings of the 2024 Annual ACM-SIAM Symposium on Discrete Algorithms (SODA)
Pages: 3089 - 3139
Editor: David P. Woodruff, Carnegie Mellon University, U.S.
DOI: 10.1137/1.9781611977912.111
ISBN (Online): 978-1-61197-791-2

# Impressions
Impressive paper on a deterministic near-linear time algorithm for finding minimum cuts in weighted graphs. The techniques used, including the clustering procedures to preserve minimum cuts, the derandomization of Karger's sampling approach, and the analysis of tree packings, are quite sophisticated.

# Key Highlights and Contributions
* Structural theorem that there exists a sparse clustering preserving minimum cuts in weighted graphs with o(1) error. This extends previous exact results for simple graphs and approximate results for weighted graphs.
* Constructs the clustering deterministically in near-linear time by building on and extending techniques for simple graphs, while overcoming significant challenges in the weighted setting.
* Reduces the polylogarithmic-approximate clusterings to 1+o(1/log n)-approximate by leveraging properties of tree packings in the presence of a wide range of edge weights. This allows recursive application over O(log n) levels.
* Combines above contributions with Li's framework of using approximate clusterings to derandomize Karger's approach yields the first deterministic near-linear time algorithm for minimum cut in weighted graphs.

# Technical Approach
Using the clusterings to recursively uncross and sparsify the graph while preserving cuts, and then applying tree packings and Karger's contraction algorithm on the skeleton graph seem to be the key elements enabling the desired running time.

# Significance
Impressive technical achievement, resolving the long-standing question of finding a near-linear time deterministic minimum cut algorithm for the weighted case. The techniques introduced, especially constructing the sparse clustering deterministically, are likely to have further applications as well.