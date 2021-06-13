# Implementing Neural Network from scratch for classification task

This project aims to learn and improve the understanding of Deep Neural Nets. How they work internally and how the training is carried out. All the codes are implemented using only numpy operations - so that every step is visible and help in understanding the internal concept.

**Here I have implemented (from scratch)**:
- Logistic Regression using stochastic Gradient descent.
- Neural network showing Forward and Backward propogation and updating weights and biases using SGD.
- Using the defined Neural Net to classify 2 image classes from CIFAR-10 Dataset.
- Neural network using Adam Optimiser (It combines RMSProp and Momentum optimiser).

**Also tried** (not shown here but can be implemented quickly by making few changes):
- Training using Different optimisers:
	- Batched Gradient Descent
	- Mini-Batch Gradient Descent
	- RMSProp Optimiser (few changes on Adam)
	- Momentum Optimiser (few changes on Adam)
- Training using different Activation functions (need to implement the derivative of the activations functions too).

**Scaling the Neural Network to have multiple hidden layers** - To Scale into a Deep NN, we just need to add more parameters - Weights and biases for each of the layer and make the appropriate changes. 
