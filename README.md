Here are the total explanation about how to run our code correctly for task 1 to task 4.

Task 1:





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

















