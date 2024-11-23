# 5-Layer Zynet Neural Network Hardware Accelerator

This project implements a hardware accelerator for a 5-layer Zynet Neural Network on a Pynq Z1 FPGA. It was developed as part of the Electronics Club student project.

## Overview

The Zynet Neural Network is a deep learning model designed for various applications such as image classification, object detection, and more. This project focuses on accelerating the inference process of the Zynet model by leveraging the parallel processing capabilities of FPGAs.

The hardware accelerator is built using Verilog and consists of several key components:

- Activation Module: Implements the activation function used in the neural network.
- Model Module: Defines the architecture and connectivity of the Zynet model.
- MACs (Multiply-Accumulate Units): Performs the core computations of the neural network.

This Repository contains RTL files for activations, model, MACs
The vivado implementation can be found in this [](url)
The weight files saved as .mif can be found in this [link](https://drive.google.com/drive/folders/15szLCZFdRvnUMlb5YX9DcoSgq5tyce7Z?usp=sharing)
