# N-Puzzle Solver (BFS, DFS, A*)

A search agent that solves arbitrary 8-puzzle configurations using three classic search algorithms with performance statistics.

## Overview
Built as part of Columbia University's Artificial Intelligence course (COMS 4701). Implements Breadth-First Search, Depth-First Search, and A* Search to solve the 8-puzzle, with detailed performance metrics for each algorithm.

## Tech Stack
- **Language:** Python 3
- **Algorithms:** BFS, DFS, A* (Manhattan distance heuristic)

## Key Features
- **BFS** — optimal path, explores level by level using explicit queue
- **DFS** — memory-efficient, explores depth-first using explicit stack
- **A* Search** — optimal and efficient using Manhattan distance heuristic
- **Performance statistics collected:**
  - Path to goal
  - Cost of path
  - Nodes expanded
  - Search depth
  - Max search depth
  - Running time
  - Max RAM usage
- **Optimized frontier** — custom data structures for O(1) membership testing
- **UDLR order** — consistent child generation order

## Results
- Solves arbitrary solvable 8-puzzle instances
- A* expands significantly fewer nodes than BFS/DFS
- All algorithms complete within time limits

## What I Learned
- Search algorithm implementation and tradeoffs
- Frontier data structure design for performance
- Heuristic design (Manhattan distance, admissibility)
- Time/memory complexity analysis
- Python performance optimization (avoiding O(n) operations)

## Note
This project was completed for a course. Source code is available upon request due to course policy restrictions. I'm happy to discuss the algorithm implementations, data structure choices, and performance analysis in an interview.
