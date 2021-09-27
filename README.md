# My Assignments

## Assignment - 1

### 1. What is a neural network neuron?
A neuron in a neural network is a fundamental unit of our brain. These are inspired by the biological neurons composed one or more chemically connected neurons.
These neurons receive input from other neurons, perform some processing and produces an output.

### 2. What is the use of the learning rate?
Learning rate is a hyper parameter (set by the user) which helps a deep learning model to control the weights of the network with 
respect to loss gradient. If the the learning rate is too small it may require many updates before reaching the minimum point or 
may get stuck. Too large learning rate can cause the model to converge quickly to a suboptimal solution. The optimal learning
rate swiftly reaches the minimum point.

### 3. How are weights initialized?
Weights are randomnly initialized keeping in mind that the weights are neither too large or small to avoid exploding or vanishing gradient problem
during the forward propagation. 

### 4. What is "loss" in a neural network?
Loss helps us to understand how much the predicted value differs from actual value and the method to calculate the loss is called Loss function.

### 5. What is the "chain rule" in gradient flow?
Since the goal of every ML problem is to minimize the cost function, we use optimization algorithms like gradient descent to find the derivatives
in order to increase or decrease the weights. The chain rule is used to for calculating derivative of composite functions. If a variable `z` depends
on the variable `y`, which itself depends on variable `x`, so that `y` and `z` are dependent variables, then `z`, via the intermediate variable of `y`, depends
on `x` as well.

source: https://towardsdatascience.com/understanding-the-mathematics-behind-gradient-descent-dde5dc9be06e
