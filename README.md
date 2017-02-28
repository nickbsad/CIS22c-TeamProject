# CIS22c-TeamProject
Team Project Repository for CIS22c in Java

Graph Problem Requirements:

•	you MUST use the Graph classes that will be given in the Team Project Code file in Catalyst (not some other graph implementation)
•	your problem MUST be a subclass of the Graph class (to be given in the Team Project Code file in Catalyst), and must also be a generic class, BUT YOUR PROJECT WILL USE ONLY ONE TYPE for the generic class (still need to make the problem work for any type)
•	your subclass MUST store the graph in the Graph class, and MUST access the graph as stored in the Graph for solving the graph problem (not just store it and not use it all)
•	you may NOT change the existing classes and methods in the Graph classes, but you may add to them with permission

Team Project Requirements:
  •	include more than one graph (storing each graph in a separate file), with 7 to 25 vertices in one graph
  •	your team project MUST: 
    o	include a loop to allow solving the problem more than once in one run
    o	display a menu to the user for the following options:
      ♣	read the graph from a text file where the file name is input from the user (use the openInputFile function)
      ♣	add an edge to the graph
      ♣	remove an edge from the graph
      ♣	undo the previous removal(s) (you MUST use an ArrayStack or LinkedStack from HW#1, and you're allowed to add this as part of the Graph)
      ♣	display the graph on the screen (give the choices of Depth-First traversal or Breadth-First traversal OR adjacency list of each vertex)
      ♣	solve the problem for the graph, which would automatically display the results on the screen (NOTE: THERE MAY NOT BE A SOLUTION FOR A GIVEN GRAPH), and ask the user if the results should be saved to a text file (where the file name is input from the user)  (MORE ===>)
      ♣	write the graph to a text file (where the file name is input from the user) displaying each vertex and its adjacency list

GRAPH Problems to choose:
3.	Euler path OR circuit: An Euler path is a path that uses every edge of a graph exactly once. An Euler circuit is a circuit that uses every edge of a graph exactly once, where the edges must be connected. ▶ An Euler path starts and ends at different vertices. ▶ An Euler circuit starts and ends at the same vertex.
4.	Dijkstra's algorithm (shortest path) (discussed in Lesson 11), BUT choose a particular application: finding shortest path for what? describe your application (what do the vertices and edges represent), for example, "six degrees of separation" problem, "least number of semesters" problem
5.	Hamiltonian circuit: A Hamiltonian cycle, also called a Hamiltonian circuit, Hamilton cycle, or Hamilton circuit, is a graph cycle (i.e., closed loop) through a graph that visits each node exactly once using existing edges.
