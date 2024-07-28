# 🧠 VGG Implementation from Scratch
![image](https://github.com/user-attachments/assets/adaeb1e8-1c78-432e-9865-dc17f1bd57e3)

## Overview

This repository contains an implementation of the VGG network from scratch using PyTorch. The VGG (Visual Geometry Group) network is a deep convolutional neural network architecture that has been widely used for image classification tasks. This implementation includes the creation of convolutional layers based on different VGG variants (VGG11, VGG13, VGG16, VGG19) and a fully connected layer to output classification results.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How It Works](#how-it-works)


## Introduction

The VGG network is known for its simplicity and uniform architecture. This project demonstrates how to build a VGG network from scratch using PyTorch, showcasing the architecture and training process. The code includes support for multiple VGG variants and can be easily extended or modified for different tasks.

## Features

- **Multiple VGG Variants**: Includes configurations for VGG11, VGG13, VGG16, and VGG19.
- **Custom Convolutional Layers**: Defines convolutional layers based on the VGG architecture.
- **Fully Connected Layers**: Implements fully connected layers for classification.
- **GPU Support**: Utilizes GPU for faster computation if available.

## How It Works

1. **VGG Styles**: Defines the architecture of different VGG variants using a dictionary.
2. **VGG Network Class**: Implements the VGG network with custom convolutional layers and fully connected layers.
3. **Forward Pass**: Defines the forward pass of the network to compute output from input images.
4. **Device Selection**: Automatically selects GPU if available for faster computation.




