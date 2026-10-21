# Week 01 – XOR Neural Network

## Aim
To implement the XOR logic gate using neural networks with NumPy and Keras.

## Dataset
The XOR truth table with two binary inputs and one output.

| Input 1 | Input 2 | Output |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

## Program 1: NumPy Implementation
`NEURALNETWORK_XOR.py`

The neural network is implemented from scratch using NumPy. It uses sigmoid activation, forward propagation, backpropagation, and weight and bias updates to learn the XOR operation.

**Output screenshot:** `NEURALNETWORK_XOR_output.png`

## Program 2: Keras Implementation
`KERAS_XOR.py`

A neural network is built using Keras with:
- 2 input features
- 1 hidden layer containing 8 neurons with ReLU activation
- 1 output neuron with sigmoid activation
- Binary cross-entropy loss
- SGD optimizer with a learning rate of 0.1
- 1,000 training epochs

**Output screenshot:** `KERAS_XOR_output.png`

## Results
Both programs are designed to learn the XOR truth table. The expected output pattern for inputs (0,0), (0,1), (1,0), and (1,1) is **0, 1, 1, 0**. The Keras program also displays the model's accuracy.

## Files Included
- `NEURALNETWORK_XOR.py` – NumPy implementation
- `NEURALNETWORK_XOR_output.png` – NumPy program output
- `KERAS_XOR.py` – Keras implementation
- `KERAS_XOR_output.png` – Keras program output