A (Principle, Algorithm, and Implementation)*

A. Objective 

Find the shortest paths in a graph using the A* algorithm.
Implement the A* algorithm in Python.

B. Graph Traversal

We aim to find the shortest path connecting point A to point F in a road network, where:

The nodes of the graph represent intersections.
The edges of the graph represent roads connecting these intersections.
Each edge is weighted by the distance between the two intersections it connects.
The goal is to find the shortest path between A and F in this road network using the A* algorithm.

C. Application to the Pac-Man Game

Implement the A* heuristic search algorithm in the aStarSearch function in the search.py file.

The A* algorithm takes a heuristic function as a parameter. A heuristic function requires two parameters:

A state in the search problem.
The problem itself.
The function nullHeuristic in search.py provides a trivial example.

You can test your A* implementation by using it to find a path to a given position in a maze, using the Manhattan distance as a heuristic function (already implemented in the manhattanHeuristic function in the searchAgents.py file).
