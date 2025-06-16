# Supplementary Materials for Visual Computing Project: Autonomous Vehicle Perception

This folder contains the supplementary materials for the Autonomous Vehicle Perception project. Below is an overview of the directory structure and file contents.

## Folders

- `0. Presentation Slide and Previous Reports/`: Contains presentation materials and project documentation.
  - `Autonomous Vehicle Perception Presentation.pptx`: Presentation slide. 
  - `Project Proposal`: Initial project proposal. 
  - `Project Check-in #1`: Progress report #1. 
  - `Project Check-in #2`: Progress report #2. 
  - `Project Check-in #3`: Progress report #3. 
  
- `1. Pre-experiment/`: Contains code before starting the experiment.
  - `Download/Load Data and EDA.ipynb`: Loads image data and converts to .npy format and performs basic EDA for modeling preparation.

- `2. Pre-trained CNN/`: Contains code and model for the pre-trained ResNet50.
 - `ResNet50InitialModel_Raw.ipynb`: Baseline ResNet50 model setup
 - `resnet50_model.pth`: Saved model weights

- `3. Obscured Data Preparation/`: Provides tools to generate and handle obscured images.
 - `CycleGAN_process.ipynb`: Instructions for obscuring images using CycleGAN
 - `FolderToNumpy.ipynb`: Converts image folders to .npy format
 - `npyFileOpener.ipynb`: Converts .npy arrays back to image folders for testing
 - `RunningCycleGAN.ipynb`: Generates rainy, foggy, and snowy images with CycleGAN
 - `SimpleMethod_ImageObscuration.ipynb`: Applies three classic weather effects using simple filters
 - `25/50 division for the obscured images.ipynb`: Splits images into 25/75 and 50/50 datasets for training

- `4. Transfer Learning/`:
 - `Testing GAN img.ipynb`: Transfer learning using CycleGAN-generated images
 - `Transfer Learning for Classic Obscuration.ipynb`: Transfer learning using classically filtered images



## Files
- `README.txt`: This file 




## Notes
These materials are provided to support reproducibility and transparency of the project. The folder structure is designed for clarity and ease of navigation.

