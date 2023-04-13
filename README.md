# Dijkstra Algorithm

Dijkstra's algorithm, designed by Dutch computer scientist Edsger Dijkstra in 1956 and published in 1959 calculates, the minimum cost path between vertices of a graph. Choosing a vertex as the root of the search, this algorithm calculates the minimum cost of this vertex for all the other vertices of the graph.

## ✈️ Situation

Dijkstra's algorithm can be used on several examples of distance calculation. If you be located in Paris and wish to travel to Portugal visiting Barcelona and Madrid before land in final point, Dijkstra's algorithm shows the best way to do this at the lowest cost between cities.

## 🖥️ About the code
The algorithm begins with a start point or root. Every arc that out or arrive on this root has a positive cost. At the beginning, the Cost Matrix it's full checked with infinity costs. The iterations of the code will write the costs on the locations with output arcs, while the locations with arrive arcs keep with infinity cost. 


![image](https://user-images.githubusercontent.com/75508707/231836109-7a11f4e6-ce9d-4381-8fd4-b0982bcffba8.png)


When we find a path with lowest cost, the previous root is removed and the new root is the vertex found. The process move on.
the code ends when the best path with the lowest cost to the last vertex is found. 

![image](https://user-images.githubusercontent.com/75508707/231838542-9eaa2761-85b3-43f4-93da-1e3a70d36080.png)
