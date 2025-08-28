### Generative AI Made Simple: Variational Autoencoder (VAE) on Fashion-MNIST

This repository demonstrates how to build a Variational Autoencoder (VAE) on the Fashion-MNIST dataset using PyTorch.

Learn how to compress images into a latent space, generate new fashion items, visualize the latent space, and interpolate between images.
## Project Structure

- vae_fashion_mnist.ipynb — Main notebook containing the full VAE workflow

- data/ — Fashion-MNIST dataset (downloaded automatically)

- vae_runs/ — Folder for saving generated images and reconstructions
## Quick Workflow

- Load dataset (Fashion-MNIST)

- Define VAE model (encoder + decoder + reparameterization)

- Train VAE on training data

- Visualize reconstructions and random generated samples

- Explore latent space with TSNE/PCA

- Perform latent-space interpolation between images

## Results

- The model can reconstruct images it has seen

- Generates new realistic fashion items

- Latent space shows meaningful structure with class separation

- Interpolations produce smooth transitions between items

## Features

- Convolutional Encoder + Decoder

- Reparameterization trick for stochastic latent sampling

- ELBO Loss: Reconstruction + KL Divergence

- Generate random samples and reconstructions

- Visualize latent space using TSNE/PCA

- Interpolate between two images in latent space
For a full step-by-step explanation of this project, check out my **Medium article**:  
[Generative AI from Scratch: Building a Variational Autoencoder on Fashion-MNIST](https://medium.com/@datascientist_SheezaShabbir/generative-ai-made-simple-build-your-first-variational-autoencoder-in-google-colab-b866ffb8fd9c)

You can see all the **concepts, code breakdown, and visualizations** in detail there!
## Getting Started

**Clone the repository:**

```bash
git clone https://github.com/yourusername/vae-fashion-mnist.git
**Install dependencies:**
pip install torch torchvision matplotlib tqdm scikit-learn

