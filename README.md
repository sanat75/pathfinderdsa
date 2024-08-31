Path Visualizer App

Table of Contents
Introduction
Features
Algorithms
Technologies Used
Installation
Usage
Contributing
License
Introduction
This React-based application serves as a path visualizer, demonstrating various algorithms used in graph traversal and pathfinding. It provides a visual representation of how algorithms like A*, BFS, DFS, and Dijkstra's algorithm find paths from a start node to a target node in a grid.

Features
Interactive Grid: Users can create walls, specify start and target nodes, and visualize pathfinding algorithms on a grid.
Algorithm Visualization: Supports A*, BFS, DFS, and Dijkstra's algorithms with real-time visualization.
Responsive Design: Built with Bootstrap for a mobile-friendly experience.
Customizable Grid: Users can adjust grid size to observe algorithm performance on different scales.
Algorithms
A Search:* Finds the shortest path using a heuristic function to estimate the cost to reach the target.
Breadth-First Search (BFS): Explores all neighbor nodes at the present depth before moving on to nodes at the next depth level.
Depth-First Search (DFS): Explores as far as possible along each branch before backtracking.
Dijkstra's Algorithm: Finds the shortest paths from the source node to all other nodes in a weighted graph.


Technologies Used
Frontend: React.js, HTML/CSS, Bootstrap
Algorithms: JavaScript
Deployment: Vercel

Installation ->
Clone the repository:

Copy code
git clone https://github.com/sanat75/pathfinderdsa.git
Install dependencies:

Copy code
npm install or npm i
![Screenshot 2024-07-14 035542](https://github.com/user-attachments/assets/6b7d9883-9522-46a5-81fd-75adbdafeff9)

Depth-First Search (DFS)
Overview
Depth-First Search (DFS) is a fundamental algorithm in graph theory used for traversing or searching tree or graph data structures. The algorithm starts at the root (or an arbitrary node in the case of a graph) and explores as far as possible along each branch before backtracking.
![Screenshot 2024-07-14 035336](https://github.com/user-attachments/assets/fa808c1c-7010-4473-8425-8c4202c62ea5)

Breadth-First Search (BFS)
Overview
Breadth-First Search (BFS) is a fundamental algorithm used for traversing or searching tree or graph data structures. It explores all the nodes at the present depth level before moving on to nodes at the next depth level. BFS uses a queue to keep track of the next location to visit.
![Screenshot 2024-07-14 035303](https://github.com/user-attachments/assets/e448266d-daac-49eb-895d-dfd68d5ba65c)

A* Search Algorithm
Overview
A* (pronounced "A star") is a popular pathfinding and graph traversal algorithm used in computer science. It is widely used for its efficiency in finding the shortest path from a start node to a target node, especially in weighted graphs. A* combines the strengths of Dijkstra's algorithm and Greedy Best-First-Search by using a heuristic function to guide its search.
![Screenshot 2024-07-14 035350](https://github.com/user-attachments/assets/42583a3b-27cd-49f2-b61e-4c2128df3e73)

Dijkstra's Algorithm
Overview
Dijkstra's algorithm is a fundamental algorithm used to find the shortest path between nodes in a graph, which may represent, for example, road networks. It works for both directed and undirected graphs with non-negative weights on the edges.
![Screenshot 2024-07-14 035402](https://github.com/user-attachments/assets/b583b862-3ec2-4fde-8bad-f96c89c220ba)
