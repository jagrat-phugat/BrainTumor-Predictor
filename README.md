# Brain Tumor Predictor

## Overview

This project is a Brain Tumor Detector that utilizes Convolutional Neural Networks (CNN) and OpenCV to classify images as either having a brain tumor or not. The dataset used for training and testing the model is sourced from Kaggle.

The project involves converting the image dataset into a numpy array format using OpenCV, and then feeding this data into a CNN model. The model is further refined using Dense layers to enhance its predictive performance.

## Dataset

The image dataset used for this project was obtained from [Kaggle](https://www.kaggle.com). It contains labeled images of brain scans, categorized into two classes: **Tumor** and **No Tumor**. The dataset was preprocessed using OpenCV to convert images into a format suitable for model training.

## Project Workflow

1. **Data Preprocessing**:
   - Images are read using OpenCV and converted into numpy arrays.
   
2. **Model Building**:
   - A Convolutional Neural Network (CNN) is constructed using Keras.
   - The model comprises multiple layers, including Convolutional, MaxPooling, Flatten, and Dense layers.
   
3. **Model Training**:
   - The preprocessed image data is split into training and testing sets.
   - The model is trained on the training data and validated using the testing data.

4. **Prediction**:
   - The trained model predicts whether a given brain scan image contains a tumor or not and if tumor is present what type of tumor is present.

## Libraries Used

The following libraries were used in the project:

- **OpenCV**: For reading and preprocessing images.
- **Keras**: For building and training the CNN model.
- **PIL (Pillow)**: For additional image processing and manipulation tasks.
- **Pathlib**: For handling file and directory paths.
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical operations and handling array data.
- **Matplotlib**: For visualizing model performance and data distributions.

## Installation

To run this project, you'll need to have Python installed along with the required libraries. You can install the necessary libraries using pip:


