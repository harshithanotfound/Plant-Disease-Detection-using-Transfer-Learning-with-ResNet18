# Plant-Disease-Detection-using-Transfer-Learning-with-ResNet18
Plant Disease Detection using PyTorch and Transfer Learning with ResNet18. Built an image classification model to identify plant diseases from leaf images using the PlantVillage dataset. Includes data augmentation, model evaluation, training visualizations, confusion matrix, and real-time disease prediction.
# Plant Disease Detection using Transfer Learning with ResNet18

## Project Overview

This project implements a plant disease detection system using deep learning and transfer learning. The model classifies plant leaf images into healthy and diseased categories using a pretrained ResNet18 model.

## Objective

To build an image classification model that can identify plant diseases from leaf images using PyTorch.

## Technologies Used

- Python
- PyTorch
- Torchvision
- ResNet18
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset

PlantVillage Dataset

Selected Classes:

- Tomato Healthy
- Tomato Early Blight
- Tomato Late Blight
- Potato Healthy
- Potato Early Blight
- Potato Late Blight

## Deep Learning Approach

### Transfer Learning

A pretrained ResNet18 model trained on ImageNet is used.

### Data Augmentation

The following augmentation techniques are applied:

- Resize
- Random Horizontal Flip
- Random Rotation
- Color Jitter
- Normalization

### Model Architecture

- Pretrained ResNet18
- Frozen feature extraction layers
- Custom final classification layer

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Generated Files

- plant_disease_resnet18.pth
- loss_curve.png
- accuracy_curve.png
- confusion_matrix.png

## Running Inference

1. Load the saved model file.
2. Select a plant leaf image.
3. Apply preprocessing.
4. Run prediction.
5. Display predicted disease and confidence score.

## Sample Output

Prediction: Tomato Early Blight

Confidence: 97.5%

## Conclusion

This project demonstrates how transfer learning can be used to solve real-world agricultural problems. The model successfully classifies plant diseases using plant leaf images and provides a practical example of computer vision in agriculture.
