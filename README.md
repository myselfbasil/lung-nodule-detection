# Lung Nodule Detection

## Overview

Lung cancer is one of the leading causes of cancer-related deaths worldwide. Early detection and diagnosis are critical for improving patient outcomes. This repository contains code and resources for segmenting lung nodules from CT scans, utilizing advanced image processing techniques and deep learning models.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Deep Learning Models**: Implementation of state-of-the-art models for lung nodule detection.
- **Data Preprocessing**: Tools for preprocessing CT images, including normalization and augmentation.
- **Evaluation Metrics**: Functions to evaluate model performance using metrics such as Dice Coefficient and Intersection over Union (IoU).
- **Visualization**: Utilities for visualizing detection results and model predictions.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/myselfbasil/lung-nodule-detection.git
   cd lung-nodule-detection
   ```
2. **Install Dependencies**:
   It is recommended to create a virtual environment. You can use `venv` or `conda` for this purpose. Install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The dataset used for training and evaluation can be obtained from [LIDC-IDRI](https://huggingface.co/datasets/basilshaji/lung-nodule-detection). Ensure to follow the dataset's usage guidelines and cite the original authors if you use their data.

## Model Architecture

This project implements various deep learning architectures for detection, including:

- **RetinaNet**: A residual network that helps in training deeper networks effectively.
- - **Yolov5**: An object detection algorithm is an algorithm that is capable of detecting certain objects or shapes in a given frame.

Each model is trained on the provided dataset, and hyperparameters can be adjusted in the configuration files.

## Results

The performance of the models can be evaluated using various metrics. Below are some sample results obtained from testing the model:

- **Dice Coefficient**: 0.85
- **IoU**: 0.75

Visualizations of the detection results will be included in the `results` directory after running the evaluation script.

## Deployed Model

The Lung Nodule detection model have been deployed online in huggingface, check it out:
https://huggingface.co/spaces/basilshaji/Lung_Nodule_Segmentation

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request. Ensure to follow the coding standards and include relevant tests for new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thank you to everyone and every source that contributed to the development of this project, regardless of the size of their contributions. Your support is greatly appreciated.
