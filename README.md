# FashionMNIST-Autoencoder-with-Early-Stopping-and-SSIM-Evaluation

This project implements a simple Autoencoder model trained on the FashionMNIST dataset using PyTorch. The model is designed to compress and reconstruct images, and its performance is evaluated both with Mean Squared Error (MSE) and Structural Similarity Index (SSIM).

## Features
- **Dataset**: FashionMNIST (downloaded automatically via torchvision)
- **Model**: Autoencoder with fully connected layers
- **Training**:
  - Adam optimizer
  - MSE loss function
  - Early stopping callback for avoiding overfitting
- **Evaluation**:
  - Visual comparison of original vs. reconstructed images
  - SSIM (Structural Similarity Index) for image quality assessment

## Requirements
This project was developed and tested in Google Colab. To run locally, install the following packages:

```bash
pip install torch torchvision matplotlib scipy numpy

Usage

  1. Clone the repository: git clone https://github.com/yourusername/fashionmnist-autoencoder.git
  cd fashionmnist-autoencoder

  2. Run the notebook or Python script in Google Colab or locally: python autoencoder.py

  3. The script will:

    Train the Autoencoder on the FashionMNIST dataset

    Apply early stopping if no improvement is observed

    Display reconstructed images alongside the originals

    Print the average SSIM score

Example Output

  Original vs. reconstructed FashionMNIST images

  Average SSIM score reported after evaluation


This project is released under the MIT License.
