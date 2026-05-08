# Traffic-Light-Detection-System
This repository contains implementations of advanced computer vision tasks, specifically Object Detection and Semantic Segmentation. The project utilizes industry-standard architectures to identify, localize, and classify objects within complex visual environments.

## Project Overview
The goal of this project is to demonstrate the efficacy of transfer learning in computer vision. By leveraging models pre-trained on massive datasets, we can achieve high-precision results for both bounding-box detection and pixel-level mask generation.

## Technical Architectures
* **YOLO (You Only Look Once):** Implemented for high-speed, real-time object detection. YOLO treats detection as a single regression problem, straight from image pixels to bounding box coordinates and class probabilities.
* **Faster R-CNN:** A two-stage detection framework using a ResNet-50 backbone. This model provides high accuracy for localized object identification through its Region Proposal Network (RPN).
* **Semantic Segmentation:** Utilized deep neural networks to perform pixel-wise classification, enabling the model to distinguish object boundaries from their backgrounds with granular detail.

## Dataset Information
The models in this project are trained and evaluated using the MS COCO (Common Objects in Context) dataset. COCO is a large-scale dataset designed for object detection, segmentation, and captioning.

Dataset Link: [MS COCO on Kaggle](https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset)

## Key Dependencies
* Python 3.x
* PyTorch / Torchvision
* OpenCV
* Matplotlib
* Numpy
* Pillow (PIL)

## Installation and Usage
1. Clone the repository:
   git clone https://github.com/yourusername/object-detection-segmentation.git
2. Install dependencies:
   pip install torch torchvision opencv-python matplotlib numpy pillow
3. Execution:
   Run the 'object detection.ipynb' notebook to initialize the models and perform inference on sample images.

## Performance Comparison
While Faster R-CNN provides superior localization accuracy for smaller objects, the YOLO implementation offers significantly faster inference times, making it suitable for deployment in hardware-constrained or real-time environments.


