Implement GitHub Issue #4: Testing and Debugging.

GitHub issue: https://github.com/negaromanzir-lab/Implement-Graph-Data-Structure-with-Shortest-Path-Algorithms/issues/4

Read the issue carefully and implement all its requirements.

Your task is to thoroughly test and debug the existing Graph Data Structure, Dijkstra Algorithm, Path Reconstruction, and Console Interface.

Testing requirements:

1. Graph initialization.
2. Edge insertion.
3. Directed graph behavior.
4. Undirected graph behavior.
5. Zero-weight edges.
6. Negative-weight rejection.
7. Invalid vertices.
8. Direct shortest paths.
9. Multiple alternative shortest paths.
10. Disconnected graphs.
11. Cyclic graphs.
12. Large distance calculations.
13. Path reconstruction.
14. Source equal to destination.
15. Invalid user input.

Use GoogleTest if appropriate. Otherwise, implement a structured assertion-based testing system.

Create separate test files where practical.

Check for:
- Incorrect shortest distances.
- Incorrect parent tracking.
- Memory errors.
- Integer overflow.
- Invalid memory access.
- Infinite loops.
- Unexpected crashes.

Compile using C++17 with `-Wall -Wextra -Wpedantic`.

Fix confirmed bugs without unnecessarily rewriting existing modules.

Create a testing report containing:
- Test case ID.
- Description.
- Input.
- Expected result.
- Actual result.
- Pass/Fail status.

Do not report tests as passed unless they have actually been executed.

Complete only Issue #4.