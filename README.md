# Prize Collecting - Travelling Salesman Problem **(PC-TSP)**

In the PCTSP ([Balas. 1989](https://onlinelibrary.wiley.com/doi/epdf/10.1002/net.3230190602)), each node has, not only an associated prize, but also an associated penalty. **The goal is to collect at least a minimum total prize, while minimizing the total tour length plus the sum of penalties of unvisited nodes**. In this problem, the algorithm has to decide some trade-off on the penalty for whether to visit or not a node with consider the marginal cost/tour length of visiting (which depends on the other nodes visited) and satisfy the minimum total prize constraint.


Reference: https://github.com/rafael2reis/salesman
