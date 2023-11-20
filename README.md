### Graph Intro
```
Nodes (Or Vertex) => Connected by Edges to other Nodes

Pros: Relationships
Cons: Scaling is hard

=> Great for real-world applications such as the internet
=> Google Maps, Amazon Recs, Facebook social connections, etc.
```
### Types of Graphs
```
Direct => has direction/movement towards a certain side
Undirect => Bidirectional

Weighted => information in edges (connections)
ex: shortest path from point A to point B

Edge List => [[node to node]
Adjacent List => [[connected to which node/s]]
Adjacency Matrix => Hash Table [0,1] 0 = not connected, 1 = connected
```

### Graph Implementation
```
Similar to LL's

constructor has the adj list {} and num of nodes;
to add a vertex, its like adding to a hash table => this.adjList[node] = []

to add an edge; push to the key of that hash table this.adjList[node1].push(node2)
```

```
```

```
```

```
```
