# OBST (Quadratic-Time implementation)

### Special implementation of Dynamic Programming (DP) based Optimal Binary Search Tree. Uses Knuth's Theorem, achieves Quadratic Time complexity.
  

Normal DP implementation | Knuth's Theorem based DP implementation (Knuth) | Naive Implementation
-------------------- | ------------------------ | -------------------------
Theta(n^3) | **Theta(n^2)** | Theta(n^4)
  
Uses Knuth's Theorem to achieve quadratic time complexity.  
  
### Knuth's Theorem:  
There are always roots of optimal subtrees such that root[i,j-1] <= root[i,j] <= root[i+1,j] for all 1<=i<j<=n.
