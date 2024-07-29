## Floyd-Warshall algorithm
The Floyd–Warshall algorithm is an algorithm for finding shortest paths in a weighted graph with positive or negative edge weights

## Task
Find the lengths of the shortest paths between all pairs of vertices of the given directed graph. Your code may assume that the input has already been checked for loops, parallel edges and negative cycles.

Print the pair, the distance and (optionally) the path

## To Test it
    n = 4
    edge = [[1, 3, -2], [2, 1, 4], [2, 3, 3], [3, 4, 2], [4, 2, -1]]
    floyd_algo(n, edge)
