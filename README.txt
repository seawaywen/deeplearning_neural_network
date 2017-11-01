We build a neural network and use it to predict daily bike rental ridership.

This network has 2 layers, one hidden layer and one output layer.
The hidden layer use the sigmoid function to activations
The output layer has only one node and is used for the regression.

According to the forward propagation definition: By working through each layer of the nework, 
we calculate the output for each neuron, all of the output from one layer become inputs to 
the neurons on the next layers.

Then we use backpropagation to propagate error backwards from output back to the network to 
update the weights.
