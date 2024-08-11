# Dissertation Repository: MSc in Translational Neuroscience

This repository contains the code and materials for a dissertation submitted for the degree of MSc in Translational Neuroscience at Imperial College London. The research investigates how incorporating source-specific information into models through structural modifications or input concatenation, and creating artificial clusters based on loss or features, can improve prediction performance when data come from multiple hierarchical sources with varied prediction difficulty.

## Code Files and Contents

The repository is organised into the following directories, each containing specific models developed and tested during the study:

### MNIST Dataset
- **MNIST_Baseline&Source_Path:**
  - MNIST Simple MLP
  - Source Fully Separated MLP
  - Source Final Layer Separated MLP

- **MNIST_Embedding&Concatenation:**
  - MNIST ID Embedding MLP
  - Source Embedding MLP
  - Source Concatenation MLP

- **MNIST_Loss_Dependent:**
  - MNIST Loss Dependent Final Layer Separated MLP
  - Loss Dependent Fully Separated MLP

### Minder Dataset
- **Minder_Concatenation&Embedding:**
  - Minder Source Concatenation MLP
  - Minder Source Embedding MLP

- **Minder_Feature_Clustering:**
  - Minder Two Feature Clustering MLP
  - Minder Four Feature Clustering MLP

- **Minder_ID_Embedding:**
  - Minder ID Embedding MLP

- **Minder_Loss_Dependent:**
  - Minder Loss Dependent Final Layer Separated MLP
  - Minder Fully Separated MLP

## Contributors
- **Supervisor:** Prof. Payam Barnaghi
- **Co-supervisor:** Alexander Capstick

## License
The code in this repository is licenced under a permissive MIT licence. All other content is licensed under CC BY 4.0. This means you may use any content in this repository as long as you credit the authors.
