# ANN-from-scratch

This is a jupyter notebook containing a 2-layer neural network with bias and mini-batch processing built from scratch in python. Runs on MNIST data as an example.

### Gradient Descent in Action

![](grad.gif)

- Explanation: each image is 28 by 28 pixels (so 784 pixels total). The matrix ```WT``` which takes the vector of pixel values into the first layer has dimensions 10x784. I have initialized ```WT``` using "standard examples" of 0,1,2,.. and so on. At each iteration of gradient descent, I'm resizing each row of ```WT``` to a 28x28 pixel image and printing the result. Across several thousand iterations of gradient descent, the values of ```WT``` change as depicted in the gif.

As a bonus, here's the same idea for a 1-layer network:

![](grad_1_layer.gif)
