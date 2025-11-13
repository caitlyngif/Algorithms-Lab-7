# CMPS 2200 Recitation 10## Answers

**Name:** Caitlyn Gifford

Place all written answers from `recitation-07.md` here for easier grading.



- **2)** Each n node is added to result and frontier at most once, so it's O(n) work. Each m edge is looked at twice, so that's O(m) work. Pop and add are O(1), so all together it is O(n + m) work.

- **4)** The reachable function only needs to be called at most once to determine if the graph is connected or not. If it is connected, reachable can be called from any node and return the length of the graph, since every node can reach all the others. If it is not connected, one call to reachable will return a value less than the n nodes on the graph, so we will know that it is not connected.

- **5)** The for loop runs just once, meaning O(1) time. In the case that every node is connected, it will visit every node and edge once, meaning a total work of O(n + m). 

- **7)** The work would change to O(n^2) because you'd have to scan n rows at a cost of O(n) per row to find which nodes are connected.