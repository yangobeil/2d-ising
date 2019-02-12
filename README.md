# Classifying the phases of the 2d Ising model

In this project we simulate the 2d Ising model using te Metropolis algorithm in python. The necessary libraries are the usual ones: numpy, matplotlib, math and random. We then 

The Ising part contains multiple functions that separate the algorithm in different subparts. There is then a function that runs the model and hands back the final configuration. We also implement a function to generate a dataset containing multiple simulations for different values of the temperature and other parameters. There is also a function to plot the results

The machine learning part uses keras (with a tensorflow backend) to make a neural network that predicts the phase of the Ising model. The main part of this section contains a function that does the training and gives the accuracy on a test set.
