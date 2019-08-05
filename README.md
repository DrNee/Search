# Search
In this project, completed for CS188 (Introduction to Artifical Intelligence), Pacman explores mazes with the goal of eating all of the pellets (Food Problem) and visiting all corners (Corner Problem).

First, using the provided stack, queue, and priority queue, I implemented Depth-First Search, Breadth-First Search, Uniform-Cost Search, and A* search. Then, after creating a graph where the nodes are gamestates, I run a graph search of this structure for the goal state (all food eaten or four corners visited) with an admissible heuristic for A* and have Pacman complete the route found (visualized in GUI). I can then compare the number of nodes explored, time, and experiment with the trade-off between heuristic complexity and number of explored nodes.

![Imgur](https://imgur.com/cWclvib)
