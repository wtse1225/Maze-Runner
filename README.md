# Maze-Runner
This maza runner function is a recursive function that finds a path from one cell to another in a maze represented as a grid of cells separated by walls. A Maze class is created and that defines the maze and has methods to help navigate it.

This function takes in the maze object, the cell number to start from, and the cell number to reach, and returns a list of all the cell numbers along the path from the start cell to the end cell. The maze is described as having row x col cells, and walls are defined by the two cell numbers they separate. The pathfinding function should return a unique path if one exists.

If every single wall existed, there would be (row-1)(col) + (col-1)(row) walls.
```
  0 |  1 |  2 |  3 
-------------------  
  4 |  5 |  6 |  7
--------------------
  8 |  9 | 10 | 11
```
For example, suppose the from_cell was 0 and the to_cell was 3, using the maze below:
The find_path function would return this path: [0, 4, 5, 1, 2, 3]
```
  0 |  1    2    3 
         ----------  
  4    5 |  6    7
----          
  8    9   10 | 11
```  
  
