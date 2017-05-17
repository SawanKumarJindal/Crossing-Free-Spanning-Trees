# Crossing-Free-Spanning-Trees
Spanning trees are one of the most important problems in theoretical science today. They can be seen as path finding algorithms which minimizes the cost of power networks, wiring connections, piping, automatic speech recognition, etc. In this project, we are analyzing geometric graphs and finding about the spanning trees with a special property of crossing-free nature, in them. We are using Markov Chain algorithms to sample random spanning trees. In this project we are working with complete graphs and assuming that the points are in general position (that is, there are no three or more collinear points). We are analyzing crossing-free spanning trees in such graphs. Geometrical graphs are the graphs in which vertices are defined by set of points. In particular, we are aiming to generate a random crossing-free spanning tree, as well as to count all such spanning trees for a given graph. Crossing-free structures have been investigated by the computational geometry community for decades. However, almost all of the developed (deterministic) algorithms counting these structures run in exponential time. There are a lot of approaches for finding a crossing – free spanning tree. One simple approach to find a crossing free spanning tree would be to take a vertex, and draw line segments from that vertex to every other vertex in the graph. We are using another approach to generate crossing-free spanning tree as it will help us better with our next steps. The proof of the crossing-free nature, the spanning tree property and its authenticity are included in the later sections. After generating crossing free spanning tree, we are experimenting with probabilistic Markov Chain algorithms to see if we can achieve close approximation of the answer (count of all crossing free spanning trees) in polynomial time. We have used this project to generate the crossing free spanning trees experimenting with a graph containing 5 vertices and after successful execution; we are able to generate 77 crossing free spanning trees. We tried 9200 Markov Chain steps per sample and after 378 numbers of iterations (coupon collector value), we are able to reach all states.
