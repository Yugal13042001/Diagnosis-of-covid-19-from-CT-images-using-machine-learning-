# Diagnosis-of-covid-19-from-CT-images-using-machine-learning

## Overview

This project aims to develop a machine learning model that can diagnose COVID-19 by analyzing chest CT images. Using a Convolutional Neural Network (CNN), the model is trained to distinguish between COVID-19 positive and negative cases, providing a rapid and accurate diagnostic tool.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Dataset

The project utilizes a dataset of chest CT images, which includes both COVID-19 positive and negative cases. The dataset is preprocessed to ensure consistency and quality before being fed into the model.

- **Source:** [Link to dataset if publicly available]
- **Classes:** COVID-19 Positive, COVID-19 Negative
- **Format:** DICOM, JPEG, or PNG

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/covid19-ct-diagnosis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd covid19-ct-diagnosis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To train the model or test it on new data:

1. **Training the Model:**
    ```bash
    python train.py --dataset_path path_to_dataset --epochs 50 --batch_size 32
    ```
2. **Testing the Model:**
    ```bash
    python test.py --model_path saved_model.pth --test_data path_to_test_data
    ```
3. **Inference on New Data:**
    ```bash
    python inference.py --image_path path_to_image
    ```

## Model Architecture

The model is based on a Convolutional Neural Network (CNN) architecture, specifically designed for image classification tasks. Several architectures were experimented with, including:

- **ResNet50**
- **VGG16**
- **InceptionV3**

The final model was selected based on its performance on the validation set.

## Results

- **Accuracy:** X%
- **Sensitivity:** Y%
- **Specificity:** Z%
- **AUC-ROC:** W

The model achieved strong performance, demonstrating its ability to accurately diagnose COVID-19 from CT images.



