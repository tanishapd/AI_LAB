# AI_LAB

## Overview
This lab is designed to provide hands-on experience in implementing and solving Artificial Intelligence problems using heuristic methods, search algorithms, and other foundational AI techniques.  
The exercises focus on understanding core concepts, applying algorithmic strategies, and developing practical problem-solving skills through real-world inspired AI tasks.

## Assigned Tasks

1. **Maze Solver using BFS & DFS**  
   - Use BFS to find the shortest path.
   - Use DFS to explore all possible paths and report one valid path (not necessarily the shortest).
   - Compare the number of nodes explored by BFS and DFS.
 

2. **Route Finder Using Bi-Directional BFS**  
   - Implement Bi-directional BFS to minimize the number of nodes explored inorder to solve a navigation problem.
   - Compare the performance of Bi-directional BFS with standard BFS and DFS.
   - Visualize the search process (e.g., using a library like networkx in Python).


3. **Search for Treasure using the Greedy Best-First Search**  
    - Implement the algorithm to always move to the most promising cell first (minimum heuristic value).
    - Use Manhattan distance as a heuristic function to find the treasure and visualize the grid.


4. **Uniform Cost Search for Optimal Path**  
    - Implement Uniform Cost Search to find the optimal path.
    - Compare it with Breadth First Search and Depth First Search for unweighted graph in terms of cost (nodes travelled).
    - Compare it with Best First Search for weighted graphs. 


5. **Path Planning for a Robot**  
    - Implement A* search using Manhattan distance as heuristic to grids without any diagonal movement.
    - Implement A* search using Diagonal distance as heuristic to grids that allow diagonal movement.
    - Compare the solutions given by A* (both task 1 and 2) with Greedy-best-first search (use same heuristics). 


6. A* Search for a Puzzle Solver   
    - Implement A* search using number of misplaced tiles as the heuristic function, to Solve the 15-puzzle.
    - Implement A* search using sum of Manhattan distances of all tiles from their goal positions as the heuristic function.
    - Compare the performance of the two heuristics in terms of the number of nodes explored and solution depth. 


7. **Maze Runner Game - Navigation with Multiple Goals**  
    - Each goal has equal priority or cost. Use BFS to navigate to the multiple goals.
    - Each goal has a different priority or cost. Implement A* for the navigation.
    - Analyse the trade-offs between path length and goal priority. 


8. AI Planner Using A* for Task Scheduling
    - Use A* Search where the heuristic estimates the remaining tasks' duration.
    - Modify the heuristic accordingly if the task priorities are also considered. (High values represent higher priority values)
    - Compare A* with a greedy method.   
  

10. **Genetic algorithm on a Search problem**  
    - Implement GA for 8-queens problem. Visualize the chessboard and the placement of queens for the best solution.
    - Extend the algorithm to solve the N-Queens Problem for larger values of N.
    - Compare GA with A* for the 8 Queens problem in terms of number of states explored (Heuristic function can be the number of conflicting queens in the current state).
      

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

  

