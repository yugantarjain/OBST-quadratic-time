# Optimal Binary Search Tree (Quadratic-Time implementation)

#### Special implementation of Dynamic Programming based Optimal Binary Search Tree algorithm. Uses Knuth's Theorem to achieve Quadratic Time complexity.

#### Time complexity chart:
**Current Implementation(Highy Efficient)** | Usual DP based implementation | Naive Implementation
-------------------- | ------------------------ | -------------------------
**Theta(n^2)** | Theta(n^3) | Theta(n^4)
  
#### Knuth's Theorem:  
There are always roots of optimal subtrees such that root[i,j-1] <= root[i,j] <= root[i+1,j] for all 1<=i<j<=n.
  
## Sample Input/Output

#### Input
Keys Probability = 0.15, 0.10, 0.05, 0.10, 0.20  
Dummy Keys Probablity = 0.05, 0.10, 0.05, 0.05, 0.05, 0.10

#### Output
![Output](/OBST_Output.png)

#### Reference
Introduction to Algorithms  
by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein
