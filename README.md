# Implementation of Dijkstra's Algorithm for Shortest Path

## Aim
To implement Dijkstra's Algorithm to find the shortest path from a source vertex to all other vertices in a weighted graph.

## Description
This program implements Dijkstra's Algorithm using a Min-Heap (Priority Queue). It calculates the minimum distance from the source vertex to every other vertex in a weighted graph with non-negative edge weights. The program also reconstructs and displays the shortest path for each vertex.

## Requirements
- Python 3.x
- heapq module (built-in Python library)

## Input
- A weighted graph represented as an adjacency list.
- Source vertex.

## Output
- Shortest distance from the source to every vertex.
- Shortest path from the source to every vertex.

## Algorithm Used
- Dijkstra's Algorithm
- Priority Queue (Min Heap)

## Time Complexity
- **Using Min Heap:** O((V + E) log V)

Where:
- **V** = Number of vertices
- **E** = Number of edges

## Space Complexity
- **O(V)**

## Conclusion
Dijkstra's Algorithm efficiently finds the shortest path from a source vertex to all other vertices in a weighted graph with non-negative edge weights. The use of a Min-Heap improves performance, making the algorithm suitable for large graphs.
