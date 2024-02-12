### Implement the Perceptron algorithm from scratch in Python.
- Initialize the weights with [0 0 0] and a learning rate of 0.0001.
- For each iteration, calculate the output of the Perceptron for each input in the training set.
- Use MSE to computer the error for all samples
- Update the weights using the gradient descent procedure.
- Repeat the above steps until the Perceptron converges or a maximum number of iterations is reached.
- Test the trained Perceptron on a separate test set.
- Use the step function as an activation function in the output layer

Use the IRIS Dataset for the above, considering all four features: sepal length, sepal width, petal length, and petal width, but only two classes -  Setosa, and Versicolor.  Drop the feature vectors of the other class. 