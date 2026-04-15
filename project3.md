[Back to Portfolio](./)

# Graphs via Adjacency Lists

- **Class: Data Structures & Algorithms**
- **Grade: A**
- **Language(s): C++**
- **Source Code Repository:** [mskegro/csci-315](https://github.com/mskegro/csci-315)  
  (Please [email me](mailto:mskegro@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project Description

This project implements a weighted directed graph using an adjacency list representation in C++. The graph is built as a generic template class `GraphAL<Weight>`, where vertices are indexed starting from 0 and edges carry associated weights.

The implementation supports full graph operations including adding and removing vertices and edges, depth-first and breadth-first traversals, and computing the minimum spanning tree weight using Prim's algorithm.

## How to Run the Program

To run this project, follow the steps below.

### Clone the repository

```bash
git clone https://github.com/mskegro/csci-315
cd csci-315
```

### Compile the program

```bash
g++ -std=c++17 -o graph_sim src/*.cpp test/*.cpp
```

### Run the program

```bash
./graph_sim
```

### Run memory check (optional)

```bash
valgrind --leak-check=full ./graph_sim
```

### View output

The program runs in the terminal and verifies:

- Correct graph construction via adjacency list
- Accurate depth-first and breadth-first traversals
- Proper edge and vertex addition and removal
- Correct minimum spanning tree weight using Prim's algorithm

## UI Design

This program runs in the terminal and does not include a graphical user interface. Output is displayed in the console via the `print()` method and Unity test results, confirming correct graph behavior (see Fig. 1).

![screenshot](images/lab23.png)  
Fig 1. Terminal output showing graph traversal and MST results

## 3. Additional Considerations

This project highlights important data structures and algorithms concepts such as:

- Adjacency list representation of weighted directed graphs
- Depth-first and breadth-first graph traversal algorithms
- Prim's algorithm for minimum spanning tree computation
- Dynamic memory management and Valgrind-verified leak-free code
- Unit testing with the Unity testing framework

For more details see [mskegro](https://github.com/mskegro/csci-315).

[Back to Portfolio](./)
