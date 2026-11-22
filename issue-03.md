Implement GitHub Issue #3: User Input and Shortest-Path Display.

GitHub issue: https://github.com/negaromanzir-lab/Implement-Graph-Data-Structure-with-Shortest-Path-Algorithms/issues/3

Read the issue carefully and implement all its requirements.

Requirements:

Create a user-friendly C++17 console interface that allows users to:

1. Enter the number of graph vertices.
2. Select directed or undirected graph.
3. Enter the number of edges.
4. Enter edge source, destination, and weight.
5. Select the starting vertex.
6. Select the destination vertex.
7. Calculate the shortest path.
8. Display the shortest path and total distance.

Use the existing Graph class from Issue #1 and Dijkstra implementation from Issue #2.

Example output:

================================
SHORTEST PATH RESULT
================================
Source: 0
Destination: 4
Shortest Path: 0 -> 1 -> 2 -> 3 -> 4
Total Distance: 10
================================

Input validation:
- Invalid vertex counts.
- Invalid edge counts.
- Invalid vertex indices.
- Negative edge weights.
- Non-numeric input.
- Invalid directed/undirected selection.
- Unreachable destination.

Display meaningful error messages instead of crashing.

Keep the console interface separate from the graph and algorithm logic.

Allow users to perform another calculation without restarting the program if practical.

Compile and test the complete application.

Complete only Issue #3.