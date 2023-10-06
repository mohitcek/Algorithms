# Algorithms

This repository contains algorithms to solve two problem, i.e. shortest path in a graph and strongly connected components in a directed graph.

## Shortest Path
Shortest Path is a common problem related to Graph Search, which can be solved using Dijkstra algorithm. The goal is to computes the minimum distance of each vertex in the graph from the source vertex. The directory 'Shortest Path' contains a jupyter notebook, which implement Dijkstra's algorithm on two examples to compute the minimum distance. 

## Strongly Connected Components

A strongly connected graph is a directed graph, where every vertex is reachable from every other vertex. Strongly Connected Compnents of a directed graph are subgraphs within itself that are strongly connected. The 'Strongly Connected Component' (SCC) directory contain a jupyter notebook, which implement an algorithm to compute the number of vertex in each strongly connected component of a directed graph using Depth-First Search (DFS) algorithm. The SCC are identified using the Kosaraju's Two-Pass algorithm, which implement depth-first search algorithm two times. First on the reverse graph to compute the finishing time of each vertex. Then it implement depth-first search on the actual graph but starting vertex is selected based on the finishing time of DFS algorithm on the reverse graph.
