# Operations Research

## Intro

Convex optimization has been active in my GitHub long before the existence of this repository. From <a href=https://github.com/je-suis-tm/quant-trading/tree/master/Smart%20Farmers%20project>smart farmers</a> in quant trading, <a href=https://github.com/je-suis-tm/recursion-and-dynamic-programming/blob/master/knapsack%20multiple%20choice.jl>multiple choice knapsack problem</a> in dynamic programming to <a href=https://github.com/je-suis-tm/machine-learning/blob/master/binary%20support%20vector%20machine.ipynb>support vector machine</a> in machine learning, I am always fascinated by the elegance of Lagrangian functions. As optimization problems accumulate in other repositories, it came to me that optimization problems deserve their own Guoco Tower as opposed to couch surfing in Tanjong Pagar. Since the more I learn, the more I realize how much I don’t know. Convex optimization is merely a little fish in a big pond. The big pond, operations research, covers other cools topics such as decision analysis, game theory, inventory theory, metaheuristics and queuing theory. Hence, the birth of this repository marks the beginning of my journey to the uncharted water. And I hope it motivates you to explore the unknown territory in mathematics as well.

## Applications

1. Convex Optimization
2. Decision Analysis
3. Game Theory
4. Inventory Theory
5. Metaheuristics
6. Queuing Theory

### 1. Sudoku

Sudoku is a logic-based, combinatorial number-placement puzzle. Despite its Japanese name, the game was actually invented by an American and later gained popularity in Japan. There are many ways (e.g. <a href=https://github.com/je-suis-tm/graph-theory/blob/master/sudoku.ipynb>vertex coloring</a>) for computer algorithms to solve Sudoku. Here we use Binary Integer Linear Programming to solve the puzzle via convex optimization. In this particular optimization problem, we have no objective function to maximize or minimize. We merely need to satisfy the constraints below.

* Only one element in each column
* Only one element in each row
* Only one element in each sub matrix
* Each cell in the matrix should be filled
* Given elements in the cells are set on

![alt text](https://github.com/je-suis-tm/operations-research/blob/main/preview/sudoku.png)

*Click <a href=https://github.com/je-suis-tm/operations-research/blob/main/sudoku.ipynb>here</a> to be redirected to the script.*

