# graph-coloring
Given an undirected connected graph, the task is to assign a valid coloring to the vertices of the graph.
a valid coloring is that: no two adjacent vertices have the same color.
## exact methods
One way to color the graph is to brute force it with some inner-optimization (branch and bound with prunning), this is good for small graphs but it's time consuming for dense graphs.
## heuristics
Heuristics are light greedy algorithms used to colorify the vertices in a way that is not time consuming and gives a satisfying solution (DSATUR, Welsh&Powell, Incidence Degree First).
## metaheuristics
local search algorithms (simulated annealing and it's variants)
## hyperheuristics
a control metaheuristic that chooses the optimal parameters of another metaheuristic. the search space of the control metaheuristic is the parameter range for another metaheuristic.
Machine learning can be introduced.
