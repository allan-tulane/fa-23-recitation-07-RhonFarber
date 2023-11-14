# CMPS 2200 Recitation 10## Answers

**Name:** Rhon Farber
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
The work of reachable is O(n + m). n for worst-case if all nodes are reachable, plus n for each O(n) edges that may have 2 nodes.
- **4)**
The worst case is calling reachable 1 time since reachable finds all nodes that can be reached from a given start node.
- **5)**
connected is dominated by reachable so the work for connected is also O(n + m).
- **7)**
If we switched the graph representation to an adjacency matrix the work of reachable would be O(n^2) because you're looking at every potential edge for every node, not just the existing edges.