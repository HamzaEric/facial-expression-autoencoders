# Facial Expression Autoencoders

This repository contains a collection of Jupyter Notebooks dedicated to training, analyzing, and comparing various Autoencoder architectures applied to facial expression datasets. The notebooks were originally developed and run using Google Colab[cite: 3].

## Repository Contents

The `Notebooks/` directory includes the following implementations[cite: 3]:

*   **`Basic_Autoencoders.ipynb`**[cite: 3]: Fundamentals of standard deterministic autoencoders. Covers encoder-decoder architectures, bottleneck dimensionality reduction, and basic facial expression reconstruction.
*   **`Variational_Autoencoders.ipynb`**[cite: 3]: Implementation of Variational Autoencoders (VAEs). Introduces probabilistic latent spaces, the reparameterization trick, and KL Divergence for generating novel facial expressions.
*   **`VAE_vs_AE_Latent_Space_Analysis.ipynb`**[cite: 3]: A comparative analysis of how standard autoencoders and VAEs structure their latent spaces. Visualizes the continuous, smooth distributions of VAEs against the rigid, point-based mappings of standard autoencoders for interpolating expressions.
*   **`Anomaly_Detection_&_Denoising_Autoencoders.ipynb`**[cite: 3]: Applications of autoencoders for reconstructing clean facial images from corrupted or noisy inputs, and utilizing reconstruction loss thresholds to detect anomalous data points.

## Tech Stack

*   **Language:** Python
*   **Frameworks:** PyTorch / PyTorch Lightning (recommended for deep learning model training)
*   **Environment:** Google Colab / Jupyter Notebooks[cite: 3]
*   **Data Handling:** Pandas, NumPy, Torchvision

## Getting Started

Since these notebooks were created using Google Colab[cite: 3], the easiest way to explore the code is to open them directly in the Colab environment.

1. Clone this repository to your local machine or mount it to your Google Drive.
   ```bash
   git clone [https://github.com/HamzaEric/facial-expression-autoencoders.git](https://github.com/HamzaEric/facial-expression-autoencoders.git)
