# Malaria Cell Image Classification Using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) to classify microscopic cell images into two categories:

- **Parasitized:** Infected red blood cells.
- **Uninfected:** Healthy red blood cells.

The model is developed using Python and TensorFlow/Keras.

## Technologies Used
- Python
- TensorFlow and Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and organise the malaria cell image dataset.
2. Resize images to 150 × 150 pixels.
3. Normalize image pixel values.
4. Build and train a CNN model.
5. Predict whether an image is Parasitized or Uninfected.
6. Evaluate the model using accuracy, confusion matrix, classification report, ROC curve and AUC.
7. Experiment with data augmentation to improve generalisation.

## Model Evaluation
The initial CNN achieved 50% test accuracy and an AUC of 0.57 on the available 20-image test subset.

A data augmentation experiment was also conducted. It achieved 50% test accuracy.

The limited dataset size significantly affects the reliability and generalisation of the results. Further improvement requires a larger, representative dataset and additional model experimentation.

## How to Run
1. Clone this repository.
2. Install the required libraries.
3. Download and organise the malaria cell image dataset into training and testing folders.
4. Open the Jupyter Notebook.
5. Run the cells sequentially.

## Project Status
Completed initial CNN implementation, image classification and model evaluation. Further optimisation and experimentation are possible.
