# AI-Search-Algorithms

This project focuses on exploring various AI search algorithms, both `uninformed` and `informed`, to tackle a problem involving agent movement, food consumption, and achieving optimal paths. The primary goal is to implement and compare these algorithms for solving the given problem.

## Problem Description
In this problem, we are given an `n * m` map with houses labeled as `food`, `duplicator`, or `wall`. Initially, there is one agent located at coordinates (0, 0). If an agent consumes a duplicator, it duplicates itself, and the new agent is placed at coordinates (n - 1, 0). The objective is for all the agents to consume all the food and reach the coordinates (n - 1, m - 1). We need to determine the minimum number of moves required to achieve this goal.

## Algorithms

### Uninformed Search Algorithms
- **BFS (Breadth-First Search):** Utilizes only the information from the problem definition to traverse the search space.
- **IDS (Iterative Deepening Depth-First Search):** An uninformed search strategy that combines depth-first search's space efficiency and breadth-first search's completeness.

### Informed Search Algorithms
- **A\* (A-Star):** An informed search algorithm that utilizes heuristic functions to determine the most promising path to the goal state.

## Objectives

This project involves the following objectives:
1. Define the terms 'Agent' and 'State' in the context of AI search strategies.
2. Implement BFS (Breadth-First Search).
3. Implement IDS (Iterative Deepening Depth-First Search).
4. Define a heuristic function.
5. Define an evaluation function.
6. Implement A\* (A-Star) algorithm.

Through these objectives, we aim to explore and apply a range of AI search algorithms for the given problem, gaining insights into their performance and effectiveness.
