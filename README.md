# Apple Detection Using Computer Vision

## For other ML/CV projects see [Machine Learning Projects](https://github.com/trow-land/Machine-Learning) and [Computer Vision Projects](https://github.com/trow-land/Computer-Vision-Projects)

## For University Robotics Projects see [MSc Dissertatio - Robotic Shiitake Harvest](https://github.com/trow-land/MSc-Dissertation-Shiitake-Harvest) and [Robotics](https://github.com/trow-land/Robotics)

This repository contains the implementation and comparison of different computer vision approaches to detect apples in an orchard. The primary goal of this project is to calculate and predetermine the yield of apple crops using machine vision algorithms, which helps estimate the seasonal turnover in the agricultural industry.

The project originally investicated four different computer vision approaches for apple detection:

1. Two conventional methods involving direct image manipulation
2. Two machine learning methods using deep learning algorithms, YOLO and Mask R-CNN

The project has since been extended to include other computer vision algorithms such as U-Net.

## Dataset

The dataset used for both methods consists of images with apples on trees. The dataset can be downloaded at [website](https://rsn.umn.edu/projects/orchard-monitoring/minneapple) and more information can be found at [GitHub](https://github.com/nicolaihaeni/MinneApple) and [Paper](https://arxiv.org/abs/1909.06441)

## Repository Structure

```
.
├── Conventional_ basic thresholding methods from lectures and tutorials.ipynb
├── Conventional_ non split method.ipynb
├── Conventional_ split method.ipynb
├── Implementation and Comparison of Machine Vision Algorithms for Detecting Apples at an Orchard.pdf
├── README.md
├── U-Net
└── YOLOv5_AppleDetector.ipynb

```

## Files Description

- `Conventional_ basic thresholding methods from lectures and tutorials.ipynb`: A Jupyter notebook containing the implementation of basic thresholding methods for apple detection.
- `Conventional_ non split method.ipynb`: A Jupyter notebook containing the implementation of a non-split method for apple detection using conventional techniques.
- `Conventional_ split method.ipynb`: A Jupyter notebook containing the implementation of a split method for apple detection using conventional techniques.
- `Implementation and Comparison of Machine Vision Algorithms for Detecting Apples at an Orchard.pdf`: The complete report detailing the methods, implementation, and results of the project.
- `README.md`: This README file.
- `Un-Net`: Further exploration into how U-Net, an algorithm originally developed for semantic segmentation in medical imaging, can be adapted for the detection and segmentation of apples. 
- `YOLOv5_AppleDetector.ipynb`: A Jupyter notebook containing the implementation of the YOLOv5 object detection model for apple detection.

## Getting Started

To get started with the project, clone the repository and install the required dependencies for each Jupyter notebook. Then, you can run the notebooks and explore the different computer vision methods for apple detection.

![AppleComparison](https://github.com/trow-land/images/blob/main/Apple_Comparison.png)

## Results

The results demonstrate a significant difference in accuracy between conventional and machine learning-based methods, with the YOLO object detection model proving to be the most accurate. The YOLO object detection model outperformed the conventional methods, with an overestimation of apples in the dataset by only 2.6%. In comparison, the best conventional approach counted 65.1% of the number of apples.


