# Simple Deep Neural Network(DNN)

## 1. Definition
The deep neural network(DNN) is an artificial neural network(ANN) with multiple hidden layers between the input and output layers. More details in [Deep_learning_Wikipedia](https://en.wikipedia.org/wiki/Deep_learning)
![01_dnn_structure](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_dnn_structure.png)
## 2. Feedforwoard neural network(FNN)
The signals moves in only one direction-forward-from the input layer, through the hidden layers and to the output layer in Feedforward neural network(FNN). It means that each neuron in one layer has directed connections to the neurons of the subsequent layer. The multilayer perceptron, for example, is included in this neural network. More details in [FNN_Wikipedia](https://en.wikipedia.org/wiki/Feedforward_neural_network)
![01_fnn](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_fnn.png)
## 3. Back propagation
The back propagation, simply, is kind of a gradient descent method generalized by automatic differentiation to compute the gradient of the loss function with respect to the weights of the network, and does so efficiently. This algorithm makes a prediction through forward pass at first and computes the loss. And then, it computes the gradient of the loss function with respect to each weight by the chain rule through backward pass. Finally, the back propagation algorithm updates weights to minimize loss. More details in [Backpropagation_Wikipedia](https://en.wikipedia.org/wiki/Backpropagation)
![01_forward_pass](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_forward_pass.png)
![01_back_propagation](https://github.com/ConstDahoud/simple_dnn/blob/main/images/01_back_propagation.png)
## 4. Sine regression with simple dnn
Refer to the two files '01_sine_regression_with_simple_dnn_using_gradient_tape.ipynb' and '03_sine_regression_with_simple_dnn_using_keras.ipynb' with those following figures. In addition, I converted the dataset typed in numpy to TF dataset and shuffled it in the second ipynb file. Check the difference.   
![02_regression](https://github.com/ConstDahoud/simple_dnn/blob/main/images/02_regression.png)
![02_regression_network](https://github.com/ConstDahoud/simple_dnn/blob/main/images/02_regression_network.png)
## 5. Spiral classification with simple dnn
Refer to the two files '02_spiral_classification_with_simple_dnn_using_gradient_tape.ipynb' and '02_spiral_classification_with_simple_dnn_using_keras.ipynb' with those following figures. The difference betweent the two files is that I built deeper neural network than the model in the following figure structure in the second file, so that I added he_normal initializers and changed activation relu to elu, and optimizer adam to Nadam. And, I also I converted the dataset typed in numpy to TF dataset and shuffled it. Check the difference.     
![03_classification](https://github.com/ConstDahoud/simple_dnn/blob/main/images/03_classification.png)
![03_classification_network](https://github.com/ConstDahoud/simple_dnn/blob/main/images/03_classification_network.png)
