# EX 2D BACKTRACKING - GRAPH COLORING PROBLEM
## AIM:
To solve the Graph Coloring Problem using backtracking, assigning colors to the vertices of a graph such that no two adjacent vertices share the same color while minimizing the number of colors used.



## Algorithm
1. Start with the first vertex and try assigning each of the m colors to it.
2. For each vertex, check if assigning a color is safe (i.e., no adjacent vertex has the same color).
3. If it’s safe, assign the color and recursively try to color the next vertex.
4. If all vertices are colored without conflicts, print the color assignments.
5. If no valid coloring exists, return false.
   

## Program:
```
/*
Program to implement Graph Coloring Problem using backtracking.
Developed by: kabilan T
Register Number:  212222230059
*/
```

## Output:
![204](https://github.com/user-attachments/assets/07bccd5d-e8a2-4b00-8a2a-324beec7c168)


## Result:
The Graph Coloring program executed successfully, and the colors were assigned to the vertices such that no two adjacent vertices share the same color.
