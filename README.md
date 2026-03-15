# MNIST Digit Classification

This repository contains two versions of a neural network for classifying handwritten digits from the MNIST dataset using TensorFlow/Keras.

## Notebooks

1. **Simple Neural Network (`simple_nn.ipynb`)**
   - No hidden layers  
   - Input and output layers only  
   - Images manually flattened before feeding to the model  

2. **Deep Neural Network (`deep_nn.ipynb`)**
   - Includes hidden layers (128 → 64 neurons)  
   - Uses `Flatten` layer inside the model  
   - Trained with Adam optimizer and softmax output  
   - Higher accuracy (~97%)  

## Features

- Data preprocessing: normalization (0-1 scaling)  
- Model building: simple and deep neural networks  
- Training, evaluation, and prediction  
- Visualization of sample predictions
