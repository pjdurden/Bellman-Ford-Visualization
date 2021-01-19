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

<img src="https://github.com/pjdurden/Bellman-Ford-Visualization/blob/main/Djisktrass.JPG">

# Following is the description of various useful inbuilt functions/routines that were consistently used in the source code-

void glLoadIdentity(): Sets the current change lattice to a personality network.

void glPopMatrix(): Pops from the network stack comparing to the current matrix mode

void gluOrtho2D(GLdouble left, GLdouble right, GLdouble bottom, GLdouble top): Characterizes a two-dimensional survey square shape in the plane z=0.

void glutInit(int *argc, char**argv): Instates GLUT&lt; the contentions from principle are passed in and can by the application.

<img src="https://github.com/pjdurden/Bellman-Ford-Visualization/blob/main/Djikstrass2.JPG">

void glutInitDisplaymode(unsigned int mode): Solicitations a showcase with the properties in mode. The estimation of mode is dictated by the legitimate OR of
choices including the shading model(GLUT_RGB&lt;GLUT_INDEX) and buffering (GLUT_SINGLE&lt;GLUT_DOUBLE).

void glutInitWindowPosition(int x,int y): Indicates the initial position of the upper left corner of the window in pixels.

void glViewport(int x,int y,GLsizei width,GLsizei height): Specifies a width * height viewport in pixels whose lower-left corner is at (x,y) measured from the origin of the window.

void gluLookAt(GLdouble eyex,GLdouble eyey, GLdouble eyez, GLdouble atx, GLdouble aty, GLdouble atz, GLdouble upx, GLdouble upy, GLdouble upz): Post multiplies the current matrix determined by the viewer at the eye point looking at the point with specified up direction.

void gluPerspective(GLdouble fov, GLdouble aspect, GLdouble near, GLdouble far): Defines a perspective viewing volume using the y direction field of view fov measured in degree,the aspect ratio of the front clipping plane, and the near and far distance.

<img src="https://github.com/pjdurden/Bellman-Ford-Visualization/blob/main/DJikstrass3.JPG">

# Following are the URLs of resources we reviewed before finalizing the approach of building this project-
1) https://www.researchgate.net/publication/250014977_THE_BELLMAN-FORD_ALGORITHM_AND_DISTRIBUTED_BELLMAN-FORD
2) https://www.irjet.net/archives/V3/i8/IRJET-V3I8367.pdf
3) https://iopscience.iop.org/article/10.1088/1742-6596/1007/1/012009/pdf
4) https://www.ripublication.com/ijaer18/ijaerv13n9_43.pdf
5) https://ieeexplore.ieee.org/document/7287776
6) https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm
7) https://www.programiz.com/dsa/bellman-ford-algorithm

# Requirements
Windows 7,8,10
Visual Studio 2017
GLUT 3.6 or higher





