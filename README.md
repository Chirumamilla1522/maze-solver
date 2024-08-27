# Maze Solver

This repository contains multiple algorithms to solve a maze, including A*, Dijkstra's algorithm, Depth First Search, and Breadth First Search. It uses various data structures like Fibonacci heaps and priority queues to efficiently solve different types of mazes.

## Features

- Implements multiple maze-solving algorithms:
  - A* (A-star)
  - Dijkstra's Algorithm
  - Depth First Search (DFS)
  - Breadth First Search (BFS)
  - Left Turn Algorithm
- Custom data structures used:
  - Fibonacci Heaps
  - Priority Queues
- Generates mazes of different types.
- Profiles algorithm performance.

## Project Structure

- `astar.py`: Implementation of the A* search algorithm.
- `breadthfirst.py`: Implementation of the Breadth First Search algorithm.
- `depthfirst.py`: Implementation of the Depth First Search algorithm.
- `dijkstra.py`: Implementation of Dijkstra's algorithm for shortest path finding.
- `FibonacciHeap.py`: Fibonacci heap implementation used in A* and Dijkstra's algorithms.
- `leftturn.py`: Implementation of the Left Turn algorithm.
- `mazes.py`: Maze generator and loader.
- `priority_queue.py`: Custom priority queue used for maze solving algorithms.
- `profile.py`: Script to profile the performance of different algorithms.
- `solve.py`: Main script that runs the maze solving algorithms.

## Getting Started

### Prerequisites

Make sure you have Python installed on your system. You can download it [here](https://www.python.org/downloads/).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Chirumamilla1522/maze-solver.git
    cd maze-solver
    ```

2. Install any dependencies (if necessary):

    ```bash
    pip install -r requirements.txt
    ```

### Running the Solver

To run a specific algorithm, use the `solve.py` script. For example:

```bash
python solve.py --algorithm astar
