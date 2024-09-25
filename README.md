# shortest_path_using-Belmenford

<br>Explanation:<br/>
<br>Edge Structure: Each edge in the graph is defined by:<br/>

<br>src: source vertex.<br/>
<br>dest: destination vertex.<br/>
<br>distance: distance (weight of the edge for shortest path calculation).<br/>
<br>time: time associated with traversing the edge.<br/>
<br>cost: cost associated with the edge.<br/>
<br>Initialization: We initialize three arrays to store the shortest distance, time, and cost for each vertex. These arrays are initially set to INT_MAX except for the source, which is initialized to 0.<br/>

<br>Relaxation: The Bellman-Ford algorithm works by relaxing all the edges in the graph for V-1 iterations, where V is the number of vertices.<br/>

<br>Negative Cycle Detection: After the relaxation step, the algorithm checks for any negative weight cycles by checking if any edge can be further relaxed. If so, the graph contains a negative-weight cycle.<br/>

<br>Result: After the algorithm completes, the shortest path distance, time, and cost from the source to all other vertices are printed.<br/>
