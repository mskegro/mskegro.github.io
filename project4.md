[Back to Portfolio](./)

# Dijkstra's Algorithm GPS Shortest Path Finder

- **Class: Algorithms (CSCI 415)**
- **Grade: A**
- **Language(s): C++**
- **Source Code Repository:** [mskegro/csci-415](https://github.com/mskegro/csci-415)  
  (Please [email me](mailto:mskegro@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project Description

This project implements Dijkstra's Algorithm to find the shortest path between vertices in a weighted directed graph, simulating a GPS navigation system. The program reads a graph from an input file containing edges and their distances, builds an adjacency matrix, and computes the shortest path from a user-specified starting vertex. The program displays an adjacency matrix, a step-by-step iteration table showing how vertex distances are updated at each iteration, and the final shortest distances from the starting vertex to all other vertices in the graph.

## How to Run the Program

To run this project, follow the steps below.

### 1. Clone the repository

```bash
git clone https://github.com/mskegro/csci-415
```

### 2. Navigate to the project folder

```bash
cd csci-415
```

### 3. Compile the program

```bash
g++ -std=c++17 -o gps dijkstra_gps.cpp
```

### 4. Run the program

```bash
./gps
```

### 5. View output

When prompted, enter the following:
- Input file name: `input.txt`
- Starting vertex: `d`, `e`, or `f` (or any valid vertex in the graph)

The program will then display:
- The full adjacency matrix of the graph
- A step-by-step iteration table showing how vertex distances are updated at each iteration
- Final shortest distances from the starting vertex to all other vertices

## UI Design

This program runs in the terminal and does not include a graphical user interface. The output displays the adjacency matrix, the step-by-step iteration table, and the final shortest distances in a formatted console view. Three different starting vertices were tested to demonstrate the program's correctness across multiple graph traversals.

Starting from vertex `d`, the program computes the shortest path to all reachable vertices in the graph (see Fig. 1).

![screenshot](images/dijkstra_d.png)  
Fig 1. Terminal output showing shortest path results starting from vertex 'd'

Starting from vertex `e`, the program recomputes all shortest paths from a different point in the graph (see Fig. 2).

![screenshot](images/dijkstra_e.png)  
Fig 2. Terminal output showing shortest path results starting from vertex 'e'

Starting from vertex `f`, the program demonstrates shortest path computation from a vertex deeper in the graph (see Fig. 3).

![screenshot](images/dijkstra_f.png)  
Fig 3. Terminal output showing shortest path results starting from vertex 'f'

## 3. Additional Considerations

This project highlights important algorithms and data structures concepts such as:

- Dijkstra's shortest path algorithm on weighted directed graphs
- Adjacency matrix representation of a graph
- Greedy algorithm design and iterative distance relaxation
- File I/O for reading graph data from external input files
- Step-by-step visualization of algorithm progression

For more details see [mskegro](https://github.com/mskegro/csci-415).

[Back to Portfolio](./)
