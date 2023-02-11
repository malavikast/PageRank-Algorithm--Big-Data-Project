# PageRank-Algorithm--Big-Data-Project


Implemented the PageRank Algorithm in this project using PySpark and calculated the ranks of different nodes using the Power Iteration and Naive Implementation techniques.
Although the Power Iteration technique provides the ranks of all nodes, it is vulnerable to spider traps and dead ends, which are bound to come across on the Internet. In fact, some of the ranks became zero after 250 iterations due to spider traps. As a result, we used Naive Implementation with a damping factor 'd' of 0.85 to avoid the impact of spider traps and dead ends. 
It was also observed that the node with the most incoming nodes had a higher rank.
Furthermore, it can be observed that having more number of partitions takes less time to complete the execution than having none. 
The time required to calculate the page ranks of the nodes decreases as the number of partitions increases which highlights the importance and efficiency of parallel computation in a real time scenario
