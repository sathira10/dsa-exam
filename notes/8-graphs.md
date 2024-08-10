# Graphs

## Graph Math

### Sets

### Mappings

### Ordered Pairs

## Definitions
A graph is a more general non-linear data structure than a tree, because each item (node) may have zero or more successors and predecessors.
> tree is a special case of a graph (all trees are graphs, but not all graphs are trees)

### Formal definitions

- graph?
- degree of a vertex (undirected graph) - the number of edges connected to it
- in-degree, out-degree of a vertex (directed graph) - number of edges coming in or going out
- degree of a graph - max degree of any vertex

#### Paths and cycles
- path - sequence of vertices connected by edges
- simple path - path with no repeated vertices
- cycle - a path whose first and last vertices are the same
- simple cycle - a cycle with no repeated edges or vertices (except first and last vertex )

#### Connected graphs
- connected graph - if there is a path from every vertex to every other vertex in the graph (edge direction is ignored)
- a graph that is not connected consists of a set of connected components
- we can also say one vertex is connected to another vertex if there exists a path that contains both of them
- strongly connected - A directed graph is strongly connected if there is a path from every vertex to every other vertex in the graph, respecting the direction of the edges.


### Undirected vs Directed Graphs
- undirected graph - no direction is given to its edges
- directed graph - directions are given to all its edges

### Weighted Graph
With a weighted graph each edge has a number, called a “weight” (or “cost”) assigned to it
> a weighted graph can be either a directed or an undirected graph

## Typical Operations (API)
- `Graph(int V)` - create an empty graph with V vertices
- `Graph(In in)` - create a graph from input stream
- `void addEdge(int v, int w)` - add an edge v-w
- `Iterable<Integer> adj(int v)` - vertices adjacent to v
- `int V()` - number of vertices
- `int E()` - number of edges
- `String toString()` - string representation

## Representation

Three ways to represent
1. Edge List (algorithmically bad)
2. Adjacency Matrix (large + complicated)
3. Adjacency List (commonly used)

## Shortest Path Algorithms
