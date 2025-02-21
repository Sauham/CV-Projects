# Fetus Location & Organ Detection with EDA

## Overview

This project involves using **YOLOv8** and **Roboflow** for detecting fetal locations and organs from medical images. The goal is to automate and improve the accuracy of fetal organ detection using deep learning techniques.

## Technologies Used

- **Python**: Core programming language for scripting and model training.
- **YOLOv8**: Object detection framework for identifying fetal locations.
- **Roboflow API**: Dataset management, augmentation, and pre-processing.
- **Ultralytics**: Used for training and fine-tuning the object detection model.
- **OpenCV**: Image processing and enhancement.
- **Pandas & NumPy**: Data analysis and transformation.

## Features

### Fetus Location Detection with EDA

- **Developed a YOLOv8-based detection model** to identify fetal brain locations.
- **Automated data extraction and preprocessing**, ensuring accurate model training.
- **Implemented hyperparameter tuning** using Ultralytics for optimized performance.

### Fetus Organ Location with EDA

- **Designed an object detection pipeline** to detect fetal organs using labeled datasets.
- **Automated file handling system** to manage missing label files and organize training data.
- **Optimized model performance** by implementing advanced training strategies with Ultralytics.

## Installation & Setup

1. Install dependencies:
   ```bash
   pip install roboflow ultralytics opencv-python pandas numpy
   ```
2. Download the dataset using Roboflow API.
3. Train the YOLOv8 model with the provided dataset.
4. Run the script to detect fetal locations and organs.

## Usage

- Modify dataset paths in the script as required.
- Run training scripts to fine-tune YOLO models.
- Test the trained model on new medical images.

## Contributions

Contributions are welcome! Feel free to submit issues or create pull requests for improvements.

## Repository

The project is hosted on GitHub. You can find it [here](https://github.com/Sauham/CV-Projects).

