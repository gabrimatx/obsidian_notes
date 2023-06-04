- $h(n) \text{ admissible} \iff h(n) \text{ never overestimates}$
- $h(n)\text{ consistent}\iff h(n_1)\leq h(n_2)+c(n_1,a,n_2) \text{(triangular inequality)}$.
- Remember  $h(n)\text{ admissible} \implies A^*$ is  cost optimal.
- Always remember to put the nodes to previous possible states (even if never expanded) when completing the search tree.
- Frontier sorting parameters:
	- Dijkstra/Uniform: Action cost.
	- BFS: Depth ASC.
	- DFS: Depth DESC.
	- Greedy best first: $h(n)$. 
	- A*: $h(n_2)+c(n_1,a,n_2)$.
- When doing the table steps, frontier and assignments the notation is the following:

| Steps | Frontier | Assignment|
|-------|---------|-------------|
| 0 | $<n_0^0>$ | $s_0^0 \rightarrow n_0^0$ |
| n| $<n_j^k,n_i^l,...>$|$s_j\rightarrow n_j^k$ |
Where the notation is $j=$state and $k=$frontier_added_step in $n_j^k$.






