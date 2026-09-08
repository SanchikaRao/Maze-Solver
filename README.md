# 🧩 BFS Maze Solver

A simple and efficient **Maze Solver using Breadth-First Search (BFS)** in Python.

This project demonstrates how BFS can be used for **grid traversal and shortest-path finding**. The algorithm starts from `S`, explores all possible paths level by level, avoids blocked cells (`#`), and finds the shortest path to the destination `G`.

---

## 🚀 Features

- 🔹 Breadth-First Search (BFS) implementation
- 🔹 Finds the shortest path in an unweighted grid
- 🔹 Handles walls and blocked cells
- 🔹 Uses Python's `deque` for efficient queue operations
- 🔹 Supports movement in four directions
- 🔹 Beginner-friendly implementation

---

## 🗺️ Maze Representation

The maze is represented as a 2D grid:

```text
S . # . .
# . # . #
. . . . .
. # . . .
. . . # G
