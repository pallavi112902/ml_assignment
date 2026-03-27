## Project Overview

This project studies how an artificial neural network (ANN) transforms data across its hidden layers during classification. Rather than looking only at final accuracy, the analysis focuses on the internal representations learned by the network.

A simple ANN is trained on the Fashion-MNIST dataset, and activations are extracted from the input and each hidden layer. These representations are then analysed using PCA visualisation, linear probe accuracy, and silhouette score to examine how class structure changes with depth.

The main goal is to show that hidden layers do not simply add computation. Instead, they progressively reshape raw pixel data into more organised and useful feature spaces that make classification easier.

## How to Run

Install dependencies:

`pip install torch torchvision numpy matplotlib scikit-learn`

Then run all cells in order.  
The notebook will train the model, generate all figures, print the final results, and save outputs to the `outputs/` folder.
