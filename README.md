# OBST (Quadratic-Time implementation)

### Special implementation of Dynamic Programming (DP) based Optimal Binary Search Tree.  
### Achieved by using Knuth's Theorem.  
  

Naive Implementation | Normal DP implementation | DP implementation (Knuth)
-------------------- | ------------------------ | -------------------------
Theta(n^4) | Theta(n^3) | Theta(n^2)

  
  
Uses Knuth's Theorem to achieve quadratic time complexity.  
  
### Knuth's Theorem:  
There are always roots of optimal subtrees such that root[i,j-1] <= root[i,j] <= root[i+1,j] for all 1<=i<j<=n.
