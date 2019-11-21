# OBST-quadratic-time

## Special Implementation of Optimal Binary Search Tree using Dynamic Programming in quadratic time.

### Normal Time Compelxity:   Theta(n^3)
### Time Complexity achieved: Theta(n^2)

Uses Knuth's Theorem to achieve quadratic time complexity.
Knuth's Theorem: 
There are always roots of optimal subtrees such that root[i,j-1] <= root[i,j] <= root[i+1,j] for all 1<=i<j<=n.
