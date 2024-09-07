# Vision Transformer (ViT) Implementation on Fasion_MNIST Dataset
This repository contains a Vision Transformer (ViT) implementation, which has been trained on the FMNIST dataset. The ViT architecture is a powerful model introduced by Google Research that leverages the self-attention mechanism from transformers, traditionally used in natural language processing, and applies it to image classification tasks. This project is a demonstration of the ViT's capability to classify Body wears in the FMNIST dataset.

# Overview
This project aims to provide an educational example of how the Vision Transformer (ViT) can be implemented and trained on a simple dataset like FMNIST. The FMNIST dataset contains 60,000 training images and 10,000 test images of cloths & Boots and is a common benchmark for image classification models.

# Model Architecture
The ViT model splits the input image into patches, then applies a transformer encoder to these patches. Unlike traditional convolutional neural networks (CNNs), ViT does not use convolutions but relies on self-attention mechanisms to understand the spatial relationships between different parts of the image.

# Key components of the ViT architecture include:

* __Patch Embeddings:__ The input image is divided into fixed-size patches, which are then flattened and linearly embedded.
* __Positional Encodings:__ Since transformers do not have a built-in sense of order, positional encodings are added to the patch embeddings to provide spatial information.
* __Transformer Encoder:__ Consists of multiple layers of self-attention and feed-forward networks, similar to the architecture used in natural language processing tasks.
* __Classification Head:__ A linear layer that outputs class probabilities after the transformer encoder.

![VIT](https://github.com/user-attachments/assets/23d6478d-7339-44e2-8371-f6d0659fd650)

# Results
After training, the ViT model achieved an accuracy of 87.57% on the MNIST test set. This demonstrates the effectiveness of the transformer architecture for image classification tasks, even on relatively simple datasets like FMNIST.

![Screenshot (160)](https://github.com/user-attachments/assets/73bde1da-f65f-4e0f-bd63-9dd08400c7e4)
