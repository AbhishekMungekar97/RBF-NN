# Radial-Basis-Function---Neural-Network ( For Function Approximation) 
# Function Approximation using a Non-linear Gaussian kernal Functions for varying spread parameters. 
# - I have tried approximating a simplistic function (a circle where every data point within the circle is labelled as 1, while everything outside it as -1) as a Radial Basis Fucntion Based Neural Network.
# - In this network, there are two crucial parameters :-
##  - Determining the centers of inidividual RBF nodes ( in the hidden layer of the Neural Network)
##  - Determing the spread parameter
# - This question will be explored over three different scenarios, where :-
##  - Scenario 1 : This implementation will comprise of a RBF NN based on gaussian kernal functions using a constant spread function and the entire training set as centers of the radial basis functions. The best spread parameter will be decided, using mean-squared-error difference as a metric.
##  - Scenario 2 : In this approach, the centers will be chosen randomly instead of considereing the entire dataset
##  - Scenario 3 : In this approach , the K-means algorithm will be used to obtain the centers.
