# Problems

The algorithm is a constructive heuristic, not a local search algorithm.
Starts with an empty solution and builds it from scratch by adding items until it's "finished."

A possible solution is a Hybrid approach:

Use the function `createSolution` to build a good initial solution.
Then use a local search to optimize that initial solution, by exploring the local neighborhood to find improvements.

This combined approach generates a significantly better final solution.

I add the functions that I used for my program.