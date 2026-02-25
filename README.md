Pathfinding Paradigms: A Comparative Mathematical Analysis
Project Overview
This repository contains the final project for the AI/ML course. It explores the mathematical foundations and real-world applications of Shortest Path algorithms in graph theory.

Instead of merely implementing a single algorithm, this project provides a rigorous comparative analysis between Dijkstra's Algorithm, the Bellman-Ford Algorithm, and Breadth-First Search (BFS). It evaluates their performance, mathematical invariants, and constraints across different graph topologies.

Key Objectives & Applications
The core of this project is to demonstrate that algorithmic superiority is highly dependent on the problem domain. The analysis is applied to three distinct real-world scenarios:

Urban GPS Routing (Positive Weights): Demonstrating the greedy efficiency of Dijkstra's algorithm.

Financial Arbitrage (Negative Cycles): Utilizing Bellman-Ford's dynamic programming approach to detect negative weight cycles in currency exchange networks.

Social Networks (Unweighted Graphs): Proving mathematically why Dijkstra degenerates in unweighted scenarios and why BFS is the optimal choice for finding "Degrees of Separation".

Repository Structure
Shortest_Path_Analysis.ipynb: The main Jupyter Notebook containing all theoretical mathematical proofs, algorithmic implementations, data generation, and visual benchmarks.

README.md: Project overview and setup instructions.

Libraries: numpy, matplotlib, time
