# Evolutionary_Computing
Tasks for Evolutionary Computing Course at ITMO University

----

## Index
1. [First Task : Function Optimization](#first-task--function-optimization)
2. [Second Task]()
3. [Third Task]()
---

## [First Task : Function Optimization](https://github.com/Nemat-Allah-Aloush/Evolutionary_Computing/blob/main/ec_lab1_Aloush.ipynb)
The goal is to play around basic implementation of Genetic Algorithm and tune it in a way that it will able to find approximate optimal solution of given function.
The target function is modification of [Rastrgin function](https://www.sfu.ca/~ssurjano/rastr.html). It is reversed, displaced and scaled in such a way that result values are in range [0.0, 10.0].  Possible range of input variables are [-5, 5] for all variables.

[Deap](https://deap.readthedocs.io/en/master/) framework was used.

It was required that the algorithm must find solutions with fitness values around 9.9, and the algorithm successfully found solutions with best fitness value equal to 9.954.

## [Second Task](https://github.com/Nemat-Allah-Aloush/Evolutionary_Computing/blob/main/ec_lab2_Aloush.ipynb)
The goal is to develop an Evolutionary algorithm to solve the queens puzzle. This is classic optimisation problem, where you have to allocate N queens across NxN chessboard in such a way, so they will not conflict to each other. The N is a parameter and can be varied. Try to think how to represent your solutions and how to perform mutation and crossover.

[Deap](https://deap.readthedocs.io/en/master/) framework was used.

The solution is based on the following [tutorial](https://nbviewer.org/github/concision/n-queens/blob/master/notebook.ipynb).


## [Third Task]()
