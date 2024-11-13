# Flood-Segmentation-using-Unet-CNN

This project focuses on using a UNet-based deep learning model for flood segmentation in satellite imagery. By leveraging a combination of SAR data, the model effectively segments flooded regions, providing valuable insights for disaster management and response efforts.

Overview
Flood segmentation from satellite images is a challenging task due to the complexity of natural terrains and the varied appearance of water bodies. This project implements a UNet architecture, specifically tuned to work with SAR imagery and segmentation masks, to automatically detect flooded areas from given inputs.

Key Features
UNet Architecture: Employs a fully convolutional UNet model, optimized for binary segmentation tasks.
Data Preprocessing: Includes robust preprocessing steps to handle both SAR and DEM data inputs.
Custom Training Adjustments: Improvements made to batch size, normalization, and data augmentation lead to stable convergence and enhanced validation performance.
Dataset
This model uses satellite images and Digital Elevation Models (DEM) for training and validation. The dataset includes labeled examples of flood and non-flooded areas to ensure accurate segmentation.

Note: Due to some misalignment issues in the dataset, specific adjustments were applied to ensure accurate image-label pairings.
