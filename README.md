# Applied-Algorithms-Project

The goal of this project is to analyze the problem of topological sorting by comparing different topological sorting algorithms in terms of efficiency and accuracy on Directed Acyclic Graphs. Two known algorithms were implemented:
1.	DFS-Based Topological Sort: Performs a DFS traversal and notes the order in which vertices become dead ends. These vertices are stacked in reverse order to obtain a topologically sorted list.
2.	Kahn’s algorithm: Involves repeatedly identifying a source, which is a vertex with no incoming edges, in a remaining digraph and deleting it along with all the edges outgoing from it. 

These results were then compared with a custom heuristic-based algorithm, which uses the principle that nodes with more outgoing edges and fewer incoming edges are prioritized. The idea is that if a node has many things depending on it, but it doesn’t depend on much itself, it’s likely an early step.

## Technologies Used

- Python 3.10
- Jupyter Notebook
- pandas, networkx
  
