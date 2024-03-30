# Maze Solver

## Description:
The Maze Solver project is a web-based application designed to generate and solve mazes using HTML, CSS, and JavaScript. Leveraging various algorithms, both for maze generation and solving, this project offers an interactive and educational experience for users interested in maze theory and algorithmic problem-solving.

## Features:

### Maze Generation Algorithms:
1. **Kruskal's Algorithm:** This algorithm creates mazes by randomly connecting cells using minimum spanning trees, ensuring a fully connected maze without loops or cycles.
2. **Prim's Algorithm:** Utilizing a similar approach to Kruskal's, Prim's algorithm starts with a single cell and gradually adds new cells, selecting edges with the lowest weight, resulting in a maze with a distinct branching pattern.
3. **Wilson's Algorithm:** Wilson's algorithm constructs mazes by performing random walks until all cells have been visited, ensuring that every cell is reachable and eliminating the possibility of isolated areas.
4. **Recursive Division:** This method divides the maze into smaller sections recursively, creating a maze with straight walls and corridors, offering a visually distinct maze structure.

### Maze Solving Algorithms:
1. **Breadth-First Search (BFS):** BFS explores the maze by traversing each cell level by level, ensuring the shortest path is found by prioritizing cells in a breadth-first manner.
2. **A\* Algorithm:** A* employs a heuristic approach to find the optimal path from the start to the end of the maze, combining the cost of reaching a cell with an estimate of the cost to reach the goal.
3. **Dijkstra's Algorithm:** Similar to A*, Dijkstra's algorithm calculates the shortest path in a maze but does not employ a heuristic function, making it ideal for situations where the exact cost between cells is known.

## How to Use:
- Users can select their preferred maze generation algorithm to create a maze of varying complexity.
- Once the maze is generated, users can choose a solving algorithm to find the shortest path from the start to the end of the maze.
- The application provides visual feedback, displaying the process of maze generation and solving in real-time, offering an engaging user experience.

The Maze Solver project not only serves as a tool for generating and solving mazes but also as an educational resource for understanding different maze generation and solving algorithms. With its intuitive interface and dynamic visualization, users can explore the fascinating world of mazes and algorithmic problem-solving.
