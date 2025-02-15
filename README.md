# Shakespeare-Like-Text-Generation-Using-GRU-based-RNN-using-PyTorch-and-Stochastic-Gradient-Descent

# Overview

This project implements a Recurrent Neural Network (RNN) for language modeling using GRU cells in PyTorch. The model is trained on a text corpus to generate coherent sequences of words.

# Dataset

1. The model is trained on text data stored in train.txt and valid.txt.
2. A Dictionary class is used to convert words to integer indices and maintain lookup tables.
3. Preprocessing includes filtering out non-English characters and tokenizing sentences.

# Requirements

Install the necessary dependencies using:

pip install torch numpy

# Implementation Details

The notebook follows these key steps:

### Preprocessing: Loads and tokenizes text, mapping words to indices.

### Model Architecture: Implements a GRU-based RNN using PyTorch.

### Training: Optimizes the model using stochastic gradient descent.

### Evaluation: Measures perplexity to assess language generation quality.

### Inference: Generates text sequences based on a trained model.
