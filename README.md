Here are the total explanation about how to run our code correctly for task 1 to task 4.

Task 1:
This Python script provides a simulation of the Ising model to simulate opinion dynamics in a social context.  
It includes functionalities for running the simulation with custom parameters and testing its components.

Ising Model Simulation: Simulate the dynamics of opinions in a grid where each cell represents an individual's opinion, 
influenced by their neighbors and external factors.

Customizable Parameters: Adjust the influence of external factors and the tolerance level of society, which affects opinion changes.

Visual Representation: View the simulation in real-time through a visual plot that updates as the simulation progresses.

Testing: Run predefined tests to validate the correctness of the calculation functions.

Useage
You need following package:
1. Numpy
2.Matplotlib
3.argparse

To start the Ising model simulation with default settings: 
$python Task1.py -ising_model

 To specify the alpha (tolerance level) :
$python Task1.py -ising_model -alpha 10

To specify external influence parameters:
$python Task1.py -ising_model -external -0.1

To specify the alpha(tolerance level) and external influence parameters:
For example 
$python Task1.py -ising_model -alpha 0.001 -external -0.1

To run tests to verify the functionality of the calculation methods used in the simulation:
$ python Task1.py -test_ising





Task 2:

Defuant model

Introduction:
This is a simple model to simulate the opinion dynamics among individuals. In this model, you can have a look about the trend that the opinion gradually concentrates together, showing the impact between people.

Dependencies:
-Numpy
-Random
-Argparse
-Matplotlib.pyplot

Usage:
You can run my model by typing this in terminal:
Python Task2.py -defuant -beta[value] -threshold[value]

Here are also four flags you can use here:

1.-beta: default number is 0.2 

2.-Threshold: default number is 0.2

3.-defuant: [You can run this with default beta and threshold value]

4.-test_defuant:[You can test the function with different parameters for beta and threshold]






Task 3:

Features:

1.Mean Degree Calculation:
Calculates the average degree of the network by calculating the average number of connections per node.
2. Mean Clustering Coefficient:
Calculates the clustering coefficient for each node as a measure of the degree to which nodes in the graph tend to cluster together.
Provides the overall average clustering coefficient for the network.
3. Mean Path Length:
Uses a modified version of the Floyd-Warshall algorithm to calculate the shortest path between all pairs of nodes in the network.
Returns the average path length between all pairs of nodes, providing a measure of the overall navigability of the network

Requirements:

1. Python 3.x
2. Matplotlib
3. NumPy


Usage:
 -  Run the simulation by executing the following command in your terminal:
    	python   Task3.py
	
	There are three tests to get three sets of answers. It can only pass the test if Mean Degree, Mean 	Clustering Coefficient and Mean Path Length have same values that are asked.


- Run tests by executing the following command in your terminal:
    python    Task3.py
	
	This command runs tests to get Mean Degree, Mean Clustering Coefficient and Mean Path Length. The 	result should be:
	Testing ring network
	Testing one-sided network
	Testing fully connected network
	All tests passed.





Task 4:

# Small world networks

Implementation:

A ring_network is first made. The present node can connect to x nearby neighbours accordong to this code. Next, it builds a small world. In order to determine whether to link, it compares the random probability with the reconnection likelihood.


Dependencies:
- numPy
- matplotlib.pyplot
-matplotlib.cm
- argparse

Usage:
- Run the simulation by executing the following command in your terminal:

	$python Task4.py -ring_network [N]   	# This should create a ring network with a range of 1 and a size of N

	$python Task4.py -small_world [N]	 #This should create a small-worlds network with default parameters

 	$python Task4.py -small_world [N]  -re_wire [P]      #This should create a small worlds network with a re-wiring probability of P

	--N is the node numbers you input  (it's integer)
	--P is the rewire probably you input (it's float number and <=1)

	Example: $python Task4.py  -ring_network 10
			$python  Task4.py  -small_world 10
			$python  Task4.py  -small_world 10 -re_wire 0.1
















