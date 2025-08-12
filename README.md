# 8-puzzle-problem-by-bfs
📌 Aim 

To implement a program that solves the classic 8-Puzzle Problem using the Best-First Search (Greedy Best-First Search) algorithm . The program finds a path from a given start state to the goal state by exploring all possible moves systematically. 

 

Shape 

📌 Problem Statement 

The 8-puzzle problem consists of a 3x3 grid with tiles numbered 1–8 and one empty space (denoted by 0). 
The objective is to move the tiles by sliding them into the empty space until the puzzle matches the goal configuration: 

Given an initial state from the user, the program must: 

Traverse the puzzle states using Best-First Search 

Record all visited states. 

Print the traversal order. 

Reconstruct and display the final path from start to goal. 
 

Shape 

📌 Algorithm Used: Depth-First Search (DFS) 

Best-First Search is a heuristic-driven search strategy. 

At each step, it chooses the state that appears to be closest to the goal according to a heuristic function h(n). 

Unlike A* search, GBFS does not consider the cost of the path so far (g(n)), only the estimated distance to the goal. 

 

🔹 Heuristic Function 

Two common heuristics are used in the 8-puzzle problem: 

Misplaced Tiles Heuristic: Number of tiles not in their goal position. 

Manhattan Distance Heuristic: Sum of distances of each tile from its goal position. 

(You can choose either, but Manhattan Distance usually performs better.) 
