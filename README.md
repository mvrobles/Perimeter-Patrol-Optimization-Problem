# Perimeter-Patrol-Optimization-Problem
In this repository a stochastic optimal control problem is considered. We start with a flying object (such as a plane) in a 200x200 grid, and the aim is to get to the coordinates [155,157] x [155,157] trying to avoid some obstacles. In each tuple of the grid, the flying object can take 4 possible actions: going up (u), down (d), left (l) or right (r). We also consider wind, wich can de modeled on the probabilites of moving after choosing one of the four possible actions.

There are two approches: one is modeling the problem as a Markov decision problem, and the other one is modeling it as a linear optimization problem. 
