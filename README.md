# Car vs Bike Image Classification Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify images into two categories: cars and bikes.

## Dataset
The dataset contains images of cars and bikes and is divided into training, validation, and testing sets.

- Training images: 2,800
- Validation images: 600
- Test images: 600
- Image size: 224 × 224 pixels

Dataset source: [Car vs Bike Classification Dataset](https://www.kaggle.com/datasets/utkarshsaxenadn/car-vs-bike-classification-dataset)

## Model Architecture
The CNN model includes:
- Three convolutional layers
- Max pooling layers
- A fully connected layer
- Dropout for regularization
- A sigmoid output layer for binary classification

## Data Augmentation
Data augmentation was applied using rotation, width shifting, height shifting, and zooming.

## Results
The model was evaluated using:
- Test accuracy
- Classification report
- Confusion matrix
- Sample predictions

The notebook contains the detailed evaluation results and visualizations.

## Tools and Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle

## How to Use
1. Download or clone this repository.
2. Open the notebook in Jupyter Notebook or Kaggle.
3. Ensure the dataset paths are configured correctly.
4. Run the notebook cells to train and evaluate the CNN model.
