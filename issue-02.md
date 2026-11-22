Implement GitHub Issue #2: Dijkstra's Algorithm.

GitHub issue: https://github.com/negaromanzir-lab/Implement-Graph-Data-Structure-with-Shortest-Path-Algorithms/issues/2

Read the issue carefully and implement all its requirements.

Requirements:
- Implement Dijkstra's shortest-path algorithm in C++17.
- Use the Graph class implemented in Issue #1.
- Use an adjacency list and a min-priority queue.
- Calculate shortest distances from a given source vertex.
- Maintain a parent array to track previous vertices.
- Support disconnected graphs.
- Support zero-weight edges.
- Reject negative-weight edges.
- Use `long long` for distance calculations.
- Protect against integer overflow.
- Implement shortest-path reconstruction.

The implementation should be modular and must not depend on console input.

Test:
1. Direct shortest path.
2. Multiple alternative routes.
3. Shortest path through intermediate vertices.
4. Disconnected vertices.
5. Zero-weight edges.
6. Cyclic graphs.
7. Invalid source vertices.
8. Large edge weights.

Expected complexity using an adjacency list and binary min-heap: O((V + E) log V).

Inspect the existing Graph implementation before coding. Do not duplicate or unnecessarily rewrite it.

Compile and execute tests before completion.

Complete only Issue #2.