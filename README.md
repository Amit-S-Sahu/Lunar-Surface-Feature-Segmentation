# Lunar Surface Feature Segmentation

    This project utilizes Convolutional Neural Networks (CNN) and the UNet architecture to accurately segment real images of the moon, 
    distinguishing various components such as small rocks, large rocks, sky, and ground.

## Features:

- Implements CNNs, UNet architecture, and transfer learning.
- Achieves an impressive accuracy rate of 95% and an IoU (Intersection over Union) score of 1.00, ensuring precise identification and segmentation of lunar features.

## Usage:

- Download Dataset: Obtain the Artificial Lunar Rocky Landscape Dataset from Kaggle.
- Configuration: Set the img_dir and mask_dir paths in the notebook to the dataset's image and mask directories.
- Execution: Run the provided code in a Jupyter environment.

## Dataset:

Artificial Lunar Rocky Landscape Dataset: [![Kaggle](https://img.shields.io/badge/Kaggle-Download-blue)](https://www.kaggle.com/datasets/romainpessia/artificial-lunar-rocky-landscape-dataset)

## Requirements:

- Python 3.x
- Jupyter Notebook
- TensorFlow
- Keras
- NumPy
