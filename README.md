Neural Network 

This project implements a simple Multilayer Perceptron (MLP) from scratch in Python.
It is designed to show how neural networks can solve problems that are not linearly separable, such as the classic XOR logic gate.

What it does

Builds a small neural network with one hidden layer.

Uses forward propagation and backpropagation.

Trains the network to learn the XOR truth table.

Example output

After training, the network correctly classifies:

[0, 0] -> 0
[0, 1] -> 1
[1, 0] -> 1
[1, 1] -> 0

Requirements

Python 3.x

Only standard libraries (math, random)

Purpose

This code is mainly for educational use: to understand how neural networks work internally and why they are needed to solve problems that a single perceptron cannot, like XOR.
