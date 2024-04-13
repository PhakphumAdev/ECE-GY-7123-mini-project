# ECE-GY-7123 Mini Project README

## Overview
This document outlines the key configurations and results of our best-performing model, ResNet18, for the ECE-GY-7123 mini-project. The model was trained with variations in a specific hyperparameter, `C`, while other parameters were held constant.

## Model Configuration
- **Model**: ResNet18
- **Total Parameters**: 4,993,583

### Hyperparameters
- **Values of C**: [100, 150, 215, 256]
- **Optimizer**: SGD
  - **Learning Rate (lr)**: 0.01
  - **Momentum**: 0.9
  - **Weight Decay**: 0.0005
- **Scheduler**: CosineAnnealingLR
  - **T_max**: 200

### Training Details
- **Number of Epochs**: 200

## Kaggle Notebook
The training and evaluation were conducted using a Kaggle notebook. We will put the link here after the competition ends. 

## Additional Files
- **code.ipynb**: This Jupyter notebook contains the code used for the project. It provides detailed implementation insights and can be used to replicate the results or as a basis for further experimentation.

For further questions or collaboration, please refer to the contact details provided in the project repository.
