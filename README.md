## Project Overview: Apple vs. Tomato CNN Classification
This project implements a Convolutional Neural Network (CNN) to classify images of apples and tomatoes. Below is a summary of the key steps identified in the notebook:

### Importing Dependencies:

Uses TensorFlow and Keras for deep learning.

Loads the dataset from a specified directory.

### Dataset Preparation:

Images are resized to 255x255 pixels.

The dataset is split into training (80%) and validation (20%) sets.

Uses image_dataset_from_directory() for loading images with binary labels (apple or tomato).

### Model Architecture (Likely a CNN):

Will likely include convolutional, pooling, and dense layers for classification.

Uses binary classification since only two categories exist.

### Training & Validation:

The model is trained using the prepared dataset.

Validation set monitors performance to prevent overfitting.

### Evaluation & Predictions:

The model's accuracy and loss are analyzed.

The trained CNN is tested on new images for classification.
