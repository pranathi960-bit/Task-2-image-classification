# Flower Image Classification using MobileNetV2

## Project Overview

This project implements a Deep Learning Image Classification model using TensorFlow and MobileNetV2.

The model classifies flower images into five categories:

- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

Transfer Learning is used with the pretrained MobileNetV2 model to improve classification performance.

## Dataset

Dataset Used: TensorFlow Flowers Dataset (tf_flowers)

Classes:

- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

Dataset Split:

- Training Data: 80%
- Testing Data: 20%

The dataset was loaded using TensorFlow Datasets (TFDS).

## Technologies Used

- Python
- TensorFlow
- Keras
- TensorFlow Datasets (TFDS)
- NumPy
- Matplotlib
- Google Colab
- MobileNetV2

## Data Preprocessing

The following preprocessing techniques were applied:

- Image resizing to 224 × 224 pixels
- Data augmentation
- Random horizontal flipping
- Random rotation
- Random zooming
- Batch processing
- Data prefetching

These techniques help improve model generalization and reduce overfitting.

## Model Architecture

The model uses Transfer Learning with MobileNetV2.

Architecture:

1. Data Augmentation Layer
2. Rescaling Layer
3. MobileNetV2 Base Model
4. Global Average Pooling Layer
5. Dropout Layer
6. Dense Output Layer (5 Classes)

## Training Configuration

Optimizer:
- Adam

Loss Function:
- Sparse Categorical Crossentropy

Evaluation Metric:
- Accuracy

Training Parameters:
- Epochs: 5
- Image Size: 224 × 224
- Number of Classes: 5

The model was trained using GPU acceleration in Google Colab.

## Results

Test Accuracy:
- 18.80%

Test Loss:
- 21.17

The project successfully demonstrates image classification using Deep Learning and Transfer Learning techniques.

## Installation

Install the required libraries:

```bash
pip install tensorflow
pip install tensorflow-datasets
pip install numpy
pip install matplotlib
```
## Run Instructions

1. Open the notebook:
   image_classification.ipynb

2. Run all cells sequentially.

3. The notebook will:
   - Load the dataset
   - Preprocess images
   - Apply data augmentation
   - Train the MobileNetV2 model
   - Evaluate performance
   - Save the trained model
   - Perform image prediction

## Model File

Download the trained model from:

[YOUR_GOOGLE_DRIVE_LINK_HERE](https://drive.google.com/file/d/1RwLoudh9TRPmUZNaXLdjMqYf786OeuVA/view?usp=sharing)

Model Name:

flower_classifier_model.keras

## Author

Velerue Pranathi

B.Tech Student

Deep Learning Image Classification Project
