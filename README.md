# Algorithms-and-Data-Structures



# Aim
**All provided with unit tests, the program should pass all unit tests.**

*Coin change problem*

Task 1: A vending machine contains certain quantities of coins and notes, and we want to determine if it can provide a given list of changes. (Since the operating system of the vending machine runs in a Jupyter notebook, the currency it uses is the euro (€) and not the dollar ($), which is more complicated to handle in a Jupyter Notebook.) With time compleaxity of O(kn).


Recursively evaluating a mathematical expression:


Task 2: A mathematical expression is a combination of symbols (numbers, operations, etc). In this question, we limit the mathematical expressions that we consider to those that are a single number and those that take the form "(expression) operator (expression)", for instance "9", "4 + 5", "(12/3) + 5" or "(12/3) + (6-1)". We will represent these in Python using lists, where one list will contain a single expression:

    "9" is [9]
    "4 + 5" is [[4], plus, [5]]
    "(12/3) + 5" is [[[12], divide, [3]], plus, [5]]
    "(12/3) + (6-1)" is [[[12], divide, [3]], plus, [[6], minus, [1]]] 
    

Matrix Creation

Task 3:  Create a function createMatrix(A) which takes an array 𝐴 as input and returns the matrix 𝐵 as defined above. With a time compelxity of 𝑂(𝑛^2) . 

 Sorting with Duplicates
 
 Task 4: Design and implemented an algorithm which can sort this list and has average runtime in 𝑂(𝑛log𝑘). With the use of  Python 𝑙𝑖𝑠𝑡 container.

Contaminated Nodes

Task 5:You are given a tree 𝑇 with a set of nodes 𝑉. The tree 𝑇 can have arbitrary degree, i.e. nodes can have arbitrarily many children. A subset of the nodes of 𝑉, called 𝐶, is contaminated. The other nodes, called 𝑃, contain a population. Hence every node either belongs to the set 𝐶 or 𝑃. A population node in 𝑃 is safe if it is not connected to a contaminated node in 𝐶

, i.e. there exists no path between the population node and any contaminated node. The  task is to find the minimum number of edges of the tree 𝑇 that must be cut (i.e. deleted) such that all population nodes are safe.

Coin change Problem using dynamic programming 

Task 6: Alice and Bob are playing a game using a bunch of coins. The players pick several coins out of the bunch in turn. Each time a player is allowed to pick 1, 2 or 4 coins, and the player that gets the last coin is the winner. Assume that both players are very smart and he/she will try his/her best to work out a strategy to win the game. We suppose that Alice is always the first player to pick. For example, if there are 2 coins, Alice will definitely pick 2 coins and win. If there are 3 coins and Alice is still the first player to pick, no matter she picks 1 or 2 coins, Bob will get the last coin and win the game. Suppose Alice plays first. Given the number of coins, you are required to write a function coingame to calculate the winner of the game, and calculate how many different strategies there are for he/she to win the game. You must use dynamic programming to solve the problem, using a bottom-up iterative implementation.

Return the winner and number of ways to win in a tuple.

# Technology:

*Jupyter Notebook with Python 3.*

