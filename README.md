# Perfect Maze Generator

A C++ perfect maze generator developed during a Data Structures II course at Unipampa.

## Overview

This project generates perfect mazes using a graph-based Depth-First Search algorithm. Each cell is represented as a vertex, connected to adjacent cells, and the maze is carved by recursively visiting unvisited neighbors.

The generated maze is exported as a `.pbm` image file.

## Features

- Perfect maze generation
- Graph-based cell representation
- Depth-First Search traversal
- Randomized path generation
- PBM image export
- Manual memory allocation and cleanup in C++

## Technologies

- C++
- Graphs
- Depth-First Search
- Procedural Generation
- PBM Image Format

## Usage

Compile with:

```bash
make
```

or

```bash
g++ -c perfMaze.cpp vertex.cpp
g++ -o maze perfMaze.o vertex.o
```

run with:
```bash
./maze <width> <height> <imageName.pbm>
```
