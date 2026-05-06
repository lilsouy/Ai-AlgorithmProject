# My Ai Algorithms project
### Introduction
The Shortest Path Problem aims to find the most efficient path between a start point and a 
goal point within a grid-based environment. In this problem, the start point (source) 
represents the initial position, while the goal point (target) is the destination that needs to 
be reached. 

## Problem Environment 
The environment consists of multiple cells, where some cells are free and others are 
blocked by obstacles. These obstacles prevent direct movement and force the algorithm 
to search for alternative paths. 
 
## Limitations of Simple Approaches 
A simple or random search approach would be inefficient, especially in large or complex 
grids, because it may explore unnecessary paths and waste time. Therefore, an intelligent 
algorithm is required to ensure optimal performance. 
 
## Why A* Algorithm 
The A* algorithm is well-suited for this problem because it combines the actual cost from 
the start node and a heuristic estimate of the remaining distance to the goal. This allows it 
to make informed decisions and efficiently find the shortest path. 

---

 
As shown in Figure 1, the algorithm intelligently navigates through the grid, avoids 
obstacles, and selects the most optimal path toward the goal. 

<img width="800" height="712" alt="WhatsApp Image 2026-04-25 at 19 32 34" src="https://github.com/user-attachments/assets/80c60452-aaad-42d7-89a6-ac312a45daf6" />

---

## A* Algorithm Explanation 
 
The A* (A-Star) algorithm is a popular search method in artificial intelligence. 
It is mainly used to find the shortest path from a starting point to a destination. 
 
It is commonly used in: 
Navigation systems (like maps) 
Games (for finding paths for characters) 
Robotics 
 
## How A* Works 
 
The A* algorithm works by checking nodes using a cost function that includes: 
f(n) = g(n) + h(n) 
 
Where: 
g(n): The real cost from the start node to the current node 
h(n): The estimated cost from the current node to the goal(heuristic) 
f(n): The total estimated cost of the path 
 
The algorithm always picks the node with the lowest f(n) value. 

## Step-by-Step Process 
 
1.Start at the initial node (Start). 
2.Add it to a list called the open list. 
3.Pick the node with the lowest f(n) value. 
4.Move it to the closed list (nodes that have been visited). 
5.Look at its neighboring nodes. 
6.Calculate g, h, and f for each neighbor. 
7.Repeat this process until you reach the goal node. 
 
## Heuristic Function (h(n)) 
The heuristic function gives an estimate of the distance to the goal. 
 
A common way to calculate it is: 
Manhattan Distance (used in grid-based problems) 
 
Example: 
If you are at (x1, y1) and the goal is at (x2, y2): 
 
h(n) = |x1 - x2| + |y1 - y2| 
 
## Why A* is Better than BFS and DFS 
 
Compared to BFS: 
BFS finds the shortest path but checks a lot of unnecessary nodes. 
 
Compared to DFS: 
DFS might not find the shortest path at all. 

## A* is better because
It uses both actual cost and an estimate 
It is more efficient and works faster 
It finds the optimal path 

## Code Explanation
This code uses the A* algorithm to find the shortest path on a grid. 
It checks the surrounding cells and chooses the best path based on the cost. 
The algorithm uses a function to calculate the total cost, which helps it decide where to move 
next. 
It continues this process until it reaches the goal. 
If a path is found, it shows the path and its length. If not, it shows that no path was found. 
 
## Conclusion
  The A * algorithm  ultimately worked  veritably well to  break the shortest path problem. 
It could  snappily find the stylish path without wasting time  covering  gratuitous bumps. 
It was obviously more productive and yielded better results than other  styles. All  by  
each A * was a smart and  dependable  result for this kind of problem. 
