# CIFAR-10 Image Classification with Pre-trained Models

## Overview
This repository contains code for training and evaluating three popular pre-trained models (VGG16, MobileNetV2, ResNet50) on the CIFAR-10 dataset using TensorFlow and Keras.

## Installation
Make sure you have the necessary packages installed:

```bash
pip install tensorflow scikit-learn matplotlib numpy
```

## Dataset
The CIFAR-10 dataset is used for training and testing. It consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class.

## Model Architecture
Three pre-trained models are used in this project:

- VGG16
- MobileNetV2
- ResNet50

Each model is adapted for the CIFAR-10 dataset by adding a Global Average Pooling layer followed by a Dense layer with softmax activation.

## Training
The models are trained for 5 epochs with the Adam optimizer and sparse categorical crossentropy loss. The training process includes data preprocessing and augmentation.

## Evaluation
After training, each model is evaluated on the test set, and the following metrics are reported:

- Accuracy
- Classification Report
- Confusion Matrix

## Usage
To train and evaluate the models, run the provided script:

```bash
python train_and_evaluate_models.py
```

## Results
Training logs and evaluation results for each model are provided in the documentation.

## Issues and Suggestions
If you encounter any issues or have suggestions for improvements, please open an issue on GitHub.

## Acknowledgments
This code is adapted from the TensorFlow and Keras documentation. Special thanks to the authors and contributors of these projects.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
