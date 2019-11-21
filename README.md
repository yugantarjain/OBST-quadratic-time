# OBST (Quadratic-Time implementation)

#### Special implementation of Dynamic Programming based Optimal Binary Search Tree algorithm. Uses Knuth's Theorem to achieve Quadratic Time complexity.
  
Usual DP based implementation | Knuth's Theorem based DP implementation | Naive Implementation
-------------------- | ------------------------ | -------------------------
Theta(n^3) | **Theta(n^2)** | Theta(n^4)
  
#### Knuth's Theorem:  
There are always roots of optimal subtrees such that root[i,j-1] <= root[i,j] <= root[i+1,j] for all 1<=i<j<=n.

## Sample Input
Keys Probability = {0.15, 0.10, 0.05, 0.10, 0.20}. 
Dummy Keys Probablity = {0.05, 0.10, 0.05, 0.05, 0.05, 0.10}

## Output
![Output](/OBST_Output.png)
