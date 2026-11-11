# Malaria Cell Image Classification using CNN

## Project Overview
This project focuses on classifying microscopic blood cell images into two categories:
- **Parasitized:** Infected red blood cells.
- **Uninfected:** Healthy red blood cells.

A Convolutional Neural Network (CNN) was developed using TensorFlow and Keras to perform binary image classification.

## Technologies Used
- Python
- TensorFlow and Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded microscopic cell images from the training and testing folders.
2. Resized images to 150 × 150 pixels.
3. Normalized pixel values between 0 and 1.
4. Built a CNN model using convolutional and max-pooling layers.
5. Trained the model and evaluated its performance.
6. Generated predictions for individual cell images.
7. Evaluated performance using a confusion matrix, ROC curve and AUC.
8. Experimented with data augmentation to improve model performance.

## Model Architecture
The CNN consists of:
- Convolutional layers with ReLU activation.
- Max-pooling layers.
- Flatten layer.
- Fully connected dense layer.
- Dropout for regularization.
- Sigmoid output layer for binary classification.

## Results
The initial CNN model achieved:
- Test Accuracy: 50%
- ROC-AUC: 0.57

A second experiment using data augmentation was also performed. It achieved 50% test accuracy on the available test subset.

**Note:** This project was tested using a small subset of 40 images. Therefore, the results are preliminary and should not be considered representative of real-world model performance. Further training with a larger dataset and model optimization are required.

## Repository Contents
- `Malaria_cell_classification.ipynb` – Jupyter Notebook containing data preprocessing, CNN implementation, training, predictions and evaluation.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Download the malaria cell image dataset and organize it into `train` and `test` folders, each containing `Parasitized` and `Uninfected` subfolders.
4. Update the dataset path in the notebook.
5. Open the notebook in Jupyter Notebook.
6. Run the cells sequentially.

## Learning Outcome
This project provided practical experience in image preprocessing, CNN model development, binary image classification, model evaluation and experimentation with data augmentation.
