# AI-Project

**Pathfinding Algorithms: Comparative Study**

**Author: Deekshitha Chowdary Kalluri**

This repository contains the code and writeup for my term project in CIS 730 - Artificial Intelligence.

**Included Files:**

- FINAL REPORT.pdf — Complete project writeup
    
- pathfinding_algorithms.ipynb — Main Python notebook with all algorithm implementations and benchmarks
   
- FINAL PPT.pptx — Presentation slides
    
- README.txt — Project summary and submission link

**GitHub Repository:**
https://github.com/DeekshithaKalluri/Pathfinding-Project

**Project Summary:**
This project presents a comprehensive comparative study of five classical pathfinding algorithms—A*, Dijkstra’s Algorithm, Iterative Deepening Depth-First Search (IDDFS), Beam Search, and Hill Climbing—within randomly generated 2D grid-based environments.

Each algorithm is implemented from scratch in Python and evaluated under controlled experimental conditions using varying grid sizes (10×10 and 15×15) with a fixed 20% obstacle density. The evaluation focuses on three key performance metrics:
    - Path Length: Number of steps in the computed path from start to goal.
    - Execution Time: Total time (in seconds) taken to compute the path.
    - Success Rate: Proportion of runs where the algorithm successfully found a valid path.

Algorithms were tested on five different randomized mazes for each grid size to capture statistical variance and assess reliability. Visualizations of the grids before and after pathfinding were included to illustrate algorithm behavior.

🔍 Key Findings
    - A* provided the best balance of speed and optimality, consistently producing shortest paths with low runtime.
    - Dijkstra’s produced the same path quality as A* but was slower due to the absence of heuristic guidance.
    - Beam Search was faster but occasionally returned suboptimal paths depending on beam width.
    - IDDFS reliably found a path but was inefficient due to redundant exploration and depth resets.
    - Hill Climbing, while fast in successful runs, frequently failed due to its greedy nature and susceptibility to local minima.
