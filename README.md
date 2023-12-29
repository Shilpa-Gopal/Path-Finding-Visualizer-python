# Path-Finding-Visualizer using Python 

Hello there! Welcome to my path-finding visualizer! Obviously, it's inspired by Clement's original path-finding visualizer. For those who are new to this project, it's a visualization tool to visualize classic graph algorithms such as A* and more.

I was fascinated to build my own visualization tool after exploring maze generation algorithms:

## Maze Generation Algorithms

### Random Maze
It's a simple algorithm that creates walls based on the output of a random function.

### A*
A* is a graph traversal and path search algorithm, often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its O(b^d) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms that can pre-process the graph to attain better performance, as well as memory-bounded approaches. However, A* is still the best solution in many cases.

### Recursive Division
Mazes can be created with recursive division, an algorithm that works as follows: Begin with the maze's space with no walls, calling this a chamber. Divide the chamber with a randomly positioned wall (or multiple walls) where each wall contains a randomly positioned passage opening within it. Then recursively repeat the process on the subchambers until all chambers are minimum sized. This method results in mazes with long straight walls crossing their space, making it easier to see which areas to avoid.
