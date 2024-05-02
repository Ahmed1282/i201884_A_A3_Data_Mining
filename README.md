# i201884_A_A3_Data_Mining
# Transformer Autoencoder with GAN for Anomaly Detection

## Overview

This script implements a Transformer Autoencoder combined with a Generative Adversarial Network (GAN) for anomaly detection on credit card transaction data.

## Description

The script performs the following steps:

1. **Data Loading and Preprocessing**: Load the credit card transaction dataset, perform basic preprocessing such as handling missing values and duplicates, and normalize the data.

2. **Define Transformer Autoencoder Model**: Define a Transformer-based autoencoder model using PyTorch.

3. **Initialize Model, Loss Function, and Optimizer**: Initialize the autoencoder model, define the loss function (Mean Squared Error), and choose an optimizer (Adam).

4. **Prepare Data for Training**: Convert the normalized data to PyTorch tensors and set up a DataLoader for batching.

5. **Training the Autoencoder**: Train the autoencoder model using the normalized data.

6. **Save the Model**: Optionally, save the trained autoencoder model.

7. **Define Generator and Discriminator Classes**: Define classes for the generator and discriminator components of the GAN.

8. **Define GAN Components and Optimizers**: Define the generator, discriminator, and their respective optimizers.

9. **Define Contrastive Loss**: Define the contrastive loss function used for training the autoencoder with contrastive learning.

10. **Training Loop for GAN and Autoencoder**: Train the GAN and autoencoder components simultaneously.

11. **Metric Calculation**: Calculate evaluation metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and accuracy.

12. **Output Metrics**: Output the calculated metrics for each epoch.

## Usage

### Prerequisites

- Python 3.x
- PyTorch
- pandas
- matplotlib

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
