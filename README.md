# DijkstrasAlgorithm
 Dijkstra’s Algorithm Implemented Utilizing a Nested Map

# Tip Calculator

**Dijkstra’s Algorithm** finds the shortest path from one vertex to another given a graph of vertices and edges.

## Design 

* [x] Use of a hybrid of two graph data structures. Characteristics from both an adjacency list and incidence list are present using a nested map.
* [x] The function addVertex, creates a vertex to the graph with a label. It also checks that no two vertices have the same label. 
* [x] The function removeVertex, iterates through the adjacency map found at each “label” entry of the graph map, and removes the edge between the starting vertex and destination vertex. It then erases the entry from the outside, graph matrix. 
* [x] The function addEdge adds an edge between two inputted vertices. It checks that both vertices’ labels exist and are not equivalent to each other. 
* [x] The function removeEdge, removes an edge between two inputted vertex labels. As long as both labels exist, it is checked that the second vertex can be found within the adjacency map of the first vertex. If this can be found, the edge between the two labels is erased.
* [x] The function shortestPath finds the shortest possible path between two inputted vertices. 


## License

    Copyright [Juliana El Rayes]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
