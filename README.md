# Simple Deep Neural Network(DNN)

## 1. Definition
The deep neural network(DNN) is an artificial neural network(ANN) with multiple hidden layers between the input and output layers.
![01_dnn_structure](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_dnn_structure.png)
## 2. Feedforwoard neural network(FNN)
The signals moves in only one direction-forward-from the input layer, through the hidden layers and to the output layer in Feedforward neural network(FNN). It means that each neuron in one layer has directed connections to the neurons of the subsequent layer. The multilayer perceptron, for example, is included in this neural network. 
![01_fnn](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_fnn.png)
## 3. Back propagation
The back propagation, simply, is kind of a gradient descent method generalized by automatic differentiation to compute the gradient of the loss function with respect to the weights of the network, and does so efficiently. This algorithm makes a prediction through forward pass at first and computes the loss. And then, it computes the gradient of the loss function with respect to each weight by the chain rule through backward pass. Finally, the back propagation algorithm updates weights to minimize loss.
![01_forward_pass](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_forward_pass.png)
![01_back_propagation](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_back_propagation.png)
