# Audio Autoencoder

Deep learning project focused on learning compact representations of audio using autoencoders and exploring their latent space.

## Overview

This project explores the use of **autoencoders** to compress, reconstruct, and analyze audio representations from Google's **Speech Commands** dataset.

Each audio recording is transformed into a **log-Mel spectrogram**, which is then compressed by an encoder into a lower-dimensional latent representation and reconstructed by a decoder.

The main objective is to study how much the audio representation can be compressed while preserving relevant information.

Different latent space dimensions are explored (`128`, `64`, `32`, `16`, and `8`) to analyze their impact on reconstruction quality. The project also investigates the structure learned by the models in the latent space using dimensionality reduction and clustering techniques such as **PCA, t-SNE, and clustering**.

Additionally, the project explores the ability of autoencoders to perform **denoising**, evaluating how clean spectrograms can be reconstructed from inputs corrupted with different levels of noise.

Finally, the latent space is directly manipulated through **interpolation between classes** and the addition of noise to latent vectors, allowing the effect of these transformations on the reconstructed Mel spectrograms and decoded audio to be analyzed.

Overall, the project aims to understand how autoencoders compress, organize, and reconstruct acoustic information, as well as identify the minimum latent dimension that preserves an acceptable level of reconstruction quality.

## Academic Context

This project was developed as part of **TD6 – Artificial Intelligence** at Universidad Torcuato Di Tella.
