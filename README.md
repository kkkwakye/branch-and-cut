# branch-and-cut for solving Paratransit Scheduling Problem

The branch-and-cut algorithm was implemented in python 3.7 using the Spyder Integrated Development Environment (IDE) and Gurobi 9.0.0. version package. It was run on a PC with 8Gb Ram, Intel ® Core ™ i3-3120M CPU with 2.4GHz cores. Let’s consider riders who have requested for paratransit service in a day or two in advance, there is a need to pick these riders with vehicles with a certain capacity and use certain routes that will help reduce operating costs (i.e. to minimize travel distance). The operating scenarios considered in this study were; 
i.	A randomized generated pick-up points (x, y) coordinates representing latitudes and longitudes in real-life case scenarios. Greensboro latitude and longitude were used 36.0726°, -79.7920° respectively.
ii.	A generated cost using the Euclidean distances; that is the differences of the x-coordinates and the y-coordinates of each arc.
iii.	A request scenario of 10, 15, 20, 30, 40 people
iv.	Vehicle capacity of 10, 15, 20 seats
The study used Gurobi Optimizer to find the optimal solution for each case scenario. Gurobi Optimizer is a software package that aids in the computation of optimization problems. Gurobi is one of the fastest and most efficient mathematical programming solvers available for Linear Programming, Quadratic Programming, and Mixed-Integer Programming("Gurobi Optimizer - Gurobi", 2020).  In order to solve mixed-integer programming problems, Gurobi uses parallel branch-and-cut, non-classical tree-of-trees search, multiple default heuristics, solution improvement, plane cuts, and symmetry detection ("Gurobi Optimizer - Gurobi", 2020).  

How to get the Gurobi Package
Follow the instructions https://www.gurobi.com/downloads/end-user-license-agreement-academic/



