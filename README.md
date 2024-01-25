# Skin-Wrinkles-Detection-System
Skin wrinkle detection system is a machine learning model utilizing TensorFlow and VGG16 architecture. The model was trained on a dataset of skin images, distinguishing between wrinkles and non-wrinkles.

## Dataset
Dataset can be downloaded using the link https://www.kaggle.com/datasets/rishantrokaha/skin-wrinkles-vs-nonwrinkles

## Features

- Skin wrinkle detection using a VGG16-based deep learning model.
- Dataset pre-processing with data augmentation for improved model generalization.
- Training and validation pipelines for model evaluation.
- Easy-to-use functions for creating, compiling, training, and saving the skin wrinkle detection model.

### Prerequisites

- Python 3.x
- TensorFlow library
- scikit-learn library
- VGG16 architecture (available through the TensorFlow applications module)

## Models

The project uses the VGG16 architecture for skin wrinkle detection. The pre-trained weights for VGG16 are used for feature extraction.

## Results

The model is trained for 20 epochs, and the training/validation accuracy is printed during the training process. The final trained model is saved as 'wrinkles_model.h5'.

## Sample Outputs
![Screen Shot 2024-01-25 at 12 51 15 PM](https://github.com/VRAJ-07/Skin-Wrinkles-Detection-System/assets/86062890/37151199-628b-48e9-897d-2584d8484c1e)
![Screen Shot 2024-01-25 at 12 52 58 PM](https://github.com/VRAJ-07/Skin-Wrinkles-Detection-System/assets/86062890/76c2dc2b-ef1c-45f1-9fa7-ef91a3829b14)

