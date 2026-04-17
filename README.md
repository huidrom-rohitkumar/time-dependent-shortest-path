# Time-Dependent Shortest Path (Modified Dijkstra)

## Overview
This project implements a time-dependent shortest path algorithm by extending Dijkstra’s algorithm to handle dynamic constraints such as traffic signals.

## Problem Statement
In real-world routing, travel time depends not only on distance but also on time-based constraints (e.g., signal timings). The goal is to compute the earliest arrival path under periodic waiting conditions.

## Approach
- Modeled the system as a directed graph:
  - Nodes: junctions with periodic signals
  - Edges: travel time between nodes
- Modified Dijkstra’s algorithm to incorporate:
  - Waiting time at nodes
  - Time-dependent edge traversal

## Algorithm Highlights
- Maintains earliest arrival time instead of static distance
- Uses priority queue for optimal path expansion
- Guarantees correctness under non-negative time constraints

## Complexity
- Time Complexity: O((V + E) log V)
- Space Complexity: O(V + E)

## Comparison
- Compared against greedy approach
- Demonstrated suboptimality of greedy strategies using counterexamples

## Key Learnings
- Extending classical algorithms to real-world constraints
- Modeling time-dependent systems
- Trade-offs between optimality and computational efficiency

## Future Work
- Add visualization for dynamic routing
- Simulate real-world traffic scenarios
- Extend to stochastic environments

## Status
🚧 Initial README. Code and experiments will be added.
