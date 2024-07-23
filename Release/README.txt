# Pathfinding Simulation Project

## Overview

This project simulates pathfinding algorithms using A* and Dijkstra's algorithm to find the shortest path in a weighted graph. It was developed by students of Zewail City of Science and Technology for the Discrete Mathematics course (MATH 308) in Spring 2024.

### Authors:
- Saifelden Mohamed (202100432)
- Aser Osama (202101266)
- Omar Elsayed (202100597)

### Institution:
Communications and Information Engineering, Zewail City of Science and Technology

## Project Structure

### Files
- **main.cpp**: Contains the main implementation of the simulation.
- **graph.txt**: Input file containing the graph data.
- **README.txt**: This file.

### Directories
- **/src**: Source code files.
- **/include**: Header files.
- **/bin**: Compiled binaries.

## Prerequisites

- C++ Compiler
- SFML library

## Installation

1. Install the SFML library:
   ```sh
   sudo apt-get install libsfml-dev
   ```

2. Clone the repository:
   ```sh
   git clone <repository_url>
   cd pathfinding-simulation
   ```

3. Compile the project:
   ```sh
   g++ -o bin/pathfinding src/main.cpp -lsfml-graphics -lsfml-window -lsfml-system
   ```

## Usage

1. Prepare the `graph.txt` file with the graph data.
2. Run the compiled binary:
   ```sh
   ./bin/pathfinding
   ```

## Input Format

The `graph.txt` file should contain:
- Grid dimensions
- Start and end points
- Obstacles

Example:
```
10 10
0 0
9 9
1 1
1 2
...
```

## Algorithms

### A* Algorithm
Combines heuristic search with Dijkstra's algorithm to efficiently find the shortest path.

### Dijkstra's Algorithm
Explores all vertices to determine the shortest path from the source to all other vertices.

## Results

The results of the simulations will be displayed in a GUI where:
- The purple node is the end position.
- The start position is the bottom right corner.
- Red nodes are nodes that have been covered.
- Blue nodes indicate the final path.

## Conclusion

This project demonstrates the efficiency of A* compared to Dijkstra's algorithm in pathfinding tasks. A* significantly reduces the search space, leading to faster results.

## References

1. E. W. Dijkstra. "A note on two problems in connexion with graphs." Numerische Mathematik, 1959.
2. GeeksforGeeks. "A* search algorithm." 2024.
3. P. E. Hart, N. J. Nilsson, and B. Raphael. "A formal basis for the heuristic determination of minimum cost paths." IEEE Transactions on Systems Science and Cybernetics, 1968.

---

For more details, refer to the project report in `main.pdf`.

---

Feel free to reach out to the authors for any queries or contributions.