# TOR-Network-Predictor

## In this project a technique which is able to identify whether an host is generating Tor-related traffic is presented. Well-known Machine learning algorithms were used in order to evaluate the effectiveness of the proposed feature set in a real world environment.

Tor is an anonymous Internet communication system based on the second generation of onion routing network protocol. Using Tor is really difficult to trace the users Internet activity. This is the reason why the usage of Tor is intended in order to protect the privacy of users, their freedom and the ability to conduct confidential communications without being monitored. Tor is even more used by cyber-criminals in order to cover their illegal activities. The Tor community has observed, for instance an alarming increase in the number of malware that abuse the popular anonymous network to hide their command and control infrastructures.
![image](https://user-images.githubusercontent.com/43853903/95637353-26b6c980-0aaf-11eb-9f68-059af0851664.png)

## A Brief Overview of Feed Forward Neural Network
The artificial neural network is inspired from the biological neural network. Neurons are the atomic unit of a biological neural network. Each neuron consists of dendrites, nucleus, and axons. It receives signals through dendrites and is carried out through axons. The computations are performed in the nucleus. The entire network is made up of a chain of neurons. AI researchers borrowed this idea to develop the artificial neural network (ANN). In this setting, each neuron accomplishes three actions:

### 1. It accumulates input from various other neurons or inputs in a weighted manner
### 2. It sums up all input signals
### 3. Based on the summed value, it calls an activation function

Each neuron thus can classify whether a set of inputs belong to one class or another. This power is limited when only a single neuron is used. However, coining a set of neurons makes it a powerful machinery for classification and sequence labelling tasks.
A set of neuron layers can be used to create a neural network. The network architecture differs based on the objective it needs to achieve. A common network architecture is a Feed Forward Neural Network (FFN). Neurons are arranged linearly without any cycles to form a FFN. It is called feed forward because information travels in the forward direction inside the network, first through the input neurons layer, then through the hidden neuron layers, and the output neurons layer Like any supervised machine learning model, the FFN needs to be trained using labelled data.
The training is in the form of optimizing the parameters by reducing the error between the output value and the true value. One such important parameter to optimize is the weight each neuron gives to each of its input signals. For a single neuron, the weight can be easily computed using the error.
However, when a set of neurons are collated in multiple layers, it is challenging to optimize the neuron weights in multiple layers based on the error computed at the output layer. The backpropagation algorithm helps to address this issue. Backpropagation is an old technique which comes under the branch of computer algebra. Here, automatic differentiation is used to calculate the gradient that is needed in the calculation of the weights to be used in the network In a FFN, based on activation of each linked neuron, the output is obtained. The error is propagated layer by layer. Based on the correctness of the output with the final outcome, the error is calculated. This error is then in turn back propagated to fix errors of internal neurons.
For each data instance, the parameters are optimized by going through multiple iterations.
