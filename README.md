# Drone-Intrusion-Detection
Custom model (resnet+deeplab) using DSPP

This repository contains the implementation of a novel approach for drone intrusion detection systems in security and surveillance contexts. The research addresses the pressing demand for robust systems that can promptly and accurately identify drones in unauthorized areas.

# Introduction<br>
Drone intrusions pose a significant threat in various security and surveillance scenarios. Traditional methods for detecting unauthorized drones face challenges, prompting the need for innovative solutions. This project proposes a novel approach that integrates deep learning techniques with a specialized dataset containing drone intrusion scenarios and corresponding image-mask pairs.

# Methodology<br>
The proposed approach leverages deep learning architectures, specifically ResNet50 and DeepLabV3, to effectively learn spatial drone positions from the provided dataset. Additionally, a focal loss function is employed to address class imbalances and enhance the model's ability to extract nuanced features. By integrating these state-of-the-art models and loss functions, the framework aims to improve the accuracy and reliability of drone intrusion detection in diverse environmental contexts.<br>

# Implementation<br>
The implementation consists of:<br>

Data preprocessing: Preparing the dataset containing drone intrusion scenarios and image-mask pairs.
Model training: Training ResNet50 and DeepLabV3 architectures on the dataset, enhanced with the focal loss function.
Evaluation: Assessing the performance of the trained models on test data to measure their effectiveness in detecting drone intrusions.
