# DELHI METRO RAIL APPLICATION

This Java program allows users to input the names of a source and destination station within the Delhi Metro network and provides them with the shortest route along with the fare required to travel between the two points. To enhance user experience, it also includes a visual representation of the metro map to assist with navigation.

The underlying logic is built using Graph and Heap data structures. In this representation, each metro station is modeled as a node containing relevant information such as the station's name, the metro line it belongs to, and any connecting lines. The edges connecting these nodes signify the travel distance between two stations, with the edge weight corresponding to the actual distance between them.

To determine the optimal route, algorithms such as Dijkstra’s, Breadth-First Search (BFS), and Depth-First Search (DFS) are employed. These help identify the shortest path from the starting station to the destination. Once this path is established, the fare is computed based on the total travel distance. The final output includes both the route details and the calculated fare.

Main.java cointains all the major code and Heap.java contains heap implementation.

## That was all... Thank you for visiting our project!!!!  
	
