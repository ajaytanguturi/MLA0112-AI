1.	In sliding puzzle, it consists of a 3x3 grid with eight numbered tiles and one empty space. The goal of the puzzle is to rearrange the tiles from their initial, scrambled state to a goal state where the numbers are ordered from 1 to 8, with the empty space in the bottom-right corner. Implement the same using python.
2.	Write the python program to place eight queens on an 8 x 8 chessboard in such a way that no two queens threaten each other. In other words, no two queens can share the same row, column, or diagonal. Use backtracking to explore different possibilities and ensures that no two queens threaten each other.
3.	Solve the given problem using python. Consider a Water Jug problem: You are given two jugs, a 4-gallon one and a 3-gallon one. Neither has any measuring marker on it. There is a pump that can be used to fill the jugs with water. How can you get exactly 2 gallons of water into the 4-gallon jug?  Explicit Assumptions: A jug can be filled from the pump, water can be poured out of a jug onto the ground, water can be poured from one jug to another and that there are no other measuring devices available.
4.	Given an array of strings, arr[] of size N and a string S, the task is to find if it is possible to map integers value in the range [0, 9] to every alphabet that occurs in the strings, such that the sum obtained after summing the numbers formed by encoding all strings in the array is equal to the number formed by the string S using Python. Input: arr[][] = {“SEND”, “MORE”},  S = “MONEY” Output: Yes explanation:  One of the possible ways is: Map the characters as the following, ‘S’? 9, ‘E’?5, ‘N’?6, ‘D’?7, ‘M’?1, ‘O’?0, ‘R’?8, ‘Y’?2.  Now, after encoding the strings “SEND”, “MORE”, and “MONEY”, modifies to 9567, 1085 and 10652 respectively.  Thus, the sum of the values of “SEND” and “MORE” is equal to (9567+1085 = 10652), which is equal to the value of the string “MONEY”.
5.	It's a river-crossing puzzle that involves three missionaries and three cannibals who need to cross a river from one side to another. The problem comes with certain constraints:  •	There is a boat that can carry at most two people at a time.  •	On either side of the river, if the number of cannibals ever exceeds the number of missionaries, the cannibals will eat the missionaries, and the mission will fail.  The goal is to find a series of moves that allow all the missionaries and cannibals to cross the river safely. Implement the scenario using Python
6.	Imagine you have a simple autonomous vacuum cleaner, which can move around in a grid-based environment. The grid is divided into cells, some of which are dirty, and some are clean. The vacuum cleaner can move in four directions: up, down, left, and right. Its primary task is to clean all the dirty cells while minimizing its movements.  Implement the above AI problem using python.
7.	Write the python program to implement BFS
8.	Write the python program to implement DFS.
9.	Given a list of cities and the distances between each pair of cities, the objective is to find the shortest possible route that visits each city exactly once and returns to the original city (the salesman's starting point). Implement the scenario using python.
10.	Write the python program to implement Best First Search algorithm
11.	Write the python program to implement A* algorithm
12.	You are given a map with regions (represented as nodes or vertices) that need to be colored such that no adjacent regions have the same color. The goal is to find a valid coloring for the entire map. Implement in graph using python.
13.	Write the python program to implement Hill Climbing algorithm .
14.	Write the python program for Tic Tac Toe game.
15.	Write the python program to implement Minimax algorithm for gaming.
16.	Write the python program to implement Apha & Beta pruning algorithm for gaming	
17.	Write the python program to implement Decision Tree	
18.	Write the python program to implement Feed forward neural Network 	
19.	Write a python program to implement Simulated Annealing Algorithm 	
20.	Write a python program to implement Towers of Hanoi problem
21.	21.		The Monkey and Banana problem is a classic artificial intelligence problem where a monkey needs to navigate through a room to reach a bunch of bananas hanging from the ceiling. The monkey has to move a box to stand on it to reach the bananas. 
Implement the above scenario using Prolog	CO3
22.		Consider a simple knowledge base describing who loves whom. Define the following relationships in Prolog and write a query to find out who loves someone named 
"Alice." loves(john, mary). loves(jane, peter). loves(peter, alice). loves(john, alice).	CO1
23.		Write a Prolog program that calculates the sum of integers from 1 to n. Define a predicate ‘sum_up_to_n’ where the first argument is 'n' (an integer) and the second argument is the result of the sum. The sum should be computed recursively.	CO2
24.		Imagine you are managing a database that stores information about individuals, including their names and dates of birth (DOB). In Prolog, create a program that defines the following: 
1.	Define at least five individuals with their names and DOBs. 
2.	Write Prolog queries to perform the following tasks: 
a.	Retrieve the DOB of a specific person given their name. 
b.	Find all individuals who are older than a certain age (e.g., 30 years old) based on their DOBs. 
c.	Determine who is the youngest person in the database. 
d.	Check if a specific person is older than another specific person. 
Your program should include appropriate facts and rules for these tasks. Make sure to provide sample queries for each task as well	
25.	Create a Prolog program that generates exam questions related to students, teachers, subjects, and codes. In this program, you have to create a knowledge base with some facts, and then generate questions based on that knowledge. The questions will be in the format of "fill in the blank."	
26.	Write Prolog facts to represent the following information about specific planets in the PLANETS database: 
a)	Planet Mercury's distance from the Sun and mass in Earth masses. 
b)	Planet Saturn's orbital period and day length in Earth days and hours, respectively. 
c)	Write a Prolog rule to find the distance between two planets based on their positions from the Sun. Provide an example query to find the distance between Planet Venus and Planet Jupiter. 
Create a Prolog query to find all planets that are closer to the Sun than Planet Earth. List the planets that match these criteria.	CO5
27.	Write a Prolog program that calculates the factorial of a given number. Your program should include a predicate factorial that takes an input number and computes its factorial. You can use recursion for this task. Write a Prolog program that calculates the nth Fibonacci number. Your program should include a predicate Fibonacci that takes an input position n and computes the Fibonacci number at that position. Use recursion to implement the Fibonacci sequence.
28.	Write a Prolog query to determine if a specific bird can fly or not. Please provide the Prolog query and its output for the following birds: 
	Sparrow 
	Penguin 
	Eagle 
Crow (A bird not mentioned in the provided facts)	
29.	You are tasked with implementing a family tree in Prolog. Use the following information to create a family tree database: 
  John is the father of Lisa. 
  Mary is the mother of Lisa and Mike. 
  Lisa is the sister of Mike. 
  Tom is the father of Mary.
  Mike is the father of Emma. 
  Emma is the mother of Olivia. 
  Tom is the grandfather of Olivia.
  Write Prolog predicates and rules to represent this family tree and answer the following queries:
  Who is the father of Emma? 
  Who is the sister of Mike? 
  Who is the grandmother of Olivia? 
  Is John the grandfather of Olivia?
30.	Create a Prolog program to suggest a dieting system based on a specific disease involves defining rules and facts for different diseases and their corresponding dietary recommendations. Use three common health conditions: diabetes, hypertension, and obesity.	
31.	Using Prolog, you have to solve the problem of finding fruits and their colors using backtracking by defining facts and rules that describe the relationships between fruits and colors. Take sample fruits of 8 no’s. 
32.	In this program, define symptoms and conditions, create rules for diagnosis, and provide an interactive interface for patients to input their symptoms. The program then tries to diagnose the patient based on the symptoms provided. Use prolog program to implement the above scenario.	







