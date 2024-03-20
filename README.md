# Drone-Intrusion-Detection
Custom model (resnet+deeplab) using DSPP

This repository contains the implementation of a novel approach for drone intrusion detection systems in security and surveillance contexts. The research addresses the pressing demand for robust systems that can promptly and accurately identify drones in unauthorized areas.

# Introduction<br>
Drone intrusions pose a significant threat in various security and surveillance scenarios. Traditional methods for detecting unauthorized drones face challenges, prompting the need for innovative solutions. This project proposes a novel approach that integrates deep learning techniques with a specialized dataset containing drone intrusion scenarios and corresponding image-mask pairs.

# Methodology<br>
The proposed approach leverages deep learning architectures, specifically ResNet50 and DeepLabV3, to effectively learn spatial drone positions from the provided dataset. Additionally, a focal loss function is employed to address class imbalances and enhance the model's ability to extract nuanced features. By integrating these state-of-the-art models and loss functions, the framework aims to improve the accuracy and reliability of drone intrusion detection in diverse environmental contexts.<br>

# Implementation<br>
The implementation consists of:<br>

1.Data preprocessing: Preparing the dataset containing drone intrusion scenarios and image-mask pairs.<br>
2.Model training: Training ResNet50 and DeepLabV3 architectures on the dataset, enhanced with the focal loss function.<br>
3.Evaluation: Assessing the performance of the trained models on test data to measure their effectiveness in detecting drone intrusions.<br>
# Results<br>
The evaluation metrics used in the code are precision,recall,mIou. Precision measures the accuracy of positive predictions, while recall evaluates the model's ability to detect all positive instances.Additionally, the mIoU metric assesses the accuracy of segmentation masks by considering the overlap between predicted and ground truth masks.<br>

The proposed methodology outperformed the previous highest mAP of 0.66, achieving an impressive mAP of 0.97887. This indicates the superior performance and effectiveness of the approach in drone detection tasks, highlighting the significance of incorporating advanced architectural features such as DSPP for improved object detection accuracy.<br>

# Conclusion
In summary, this study offers a thorough investigation into a drone detection system that utilises the Dilated Spatial Pyramid Pooling (DSPP) module, integrated within a ResNet50 architecture and DeepLabV3 semantic segmentation framework. Through extensive experimentation and evaluation, the proposed system shows promising results in accurately identifying drones within aerial imagery across a range of environmental conditions.
Validation outcomes demonstrate the robustness and adaptability of  proposed system, consistently achieving high precision, recall, and mean Intersection over Union (mIoU) scores across various environmental settings.

# Contributors
1)Harshita (@sriharshitha07) <br>
2)Medhovarsh Bayyapureddi (@Medhovarsh) <br>
3)A Supreeth Gupta (@supre234) <br>
4)A Karthik (@Karthik554) <br>
