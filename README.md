# Generative Cooperative Networks (GCNs)

This repository contain a notebook with a novel architecture called Generative Cooperative Networks (GCNs) for image pre-processing using the CIFAR-10 dataset.

## Key functionalities:

1. **Reconstruction of Masked Images**: The generator's primary task is to reconstruct an image with a segment intentionally hidden or masked.
2. **Mask Prediction**: In contrast, the discriminator's role is to predict the mask from the image that the generator reconstructs.
3. **Pixel-wise Discrimination**: GCNs break away from GANs' sample-wise discrimination approach, adopting a more detailed pixel-wise discrimination method instead.

## Link to the notebook:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/johanhagner/Generative-Colaboratory-Networks/blob/main/gcn.ipynb)
