# Bellman-Ford-Visualization
Simulation of Bellman Ford Algorithm using GLUT openGL

# how it works
Given a graph and a source vertex src in graph, find shortest paths from src to all vertices in the given graph. The graph may contain negative weight edges.
Dijkstra’s algorithm is a Greedy algorithm and time complexity is O(VLogV) (with the use of Fibonacci heap). Dijkstra doesn’t work for Graphs with negative weight edges, Bellman-Ford works for such graphs. Bellman-Ford is also simpler than Dijkstra and suites well for distributed systems. But time complexity of Bellman-Ford is O(VE), which is more than Dijkstra.

Worst case performance: O(V*E)
Best case performance: O(E)
Worst Space complexity: O(V)

Where, V= Number of vertices in graph,
E=Number of edges in graph  


# Requirements
Windows 7,8,10
Visual Studio 2017
GLUT 3.6 or higher





