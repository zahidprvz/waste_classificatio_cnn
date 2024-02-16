# Waste Classification using Convolutional Neural Network (CNN)

This notebook showcases the development and training of a Convolutional Neural Network (CNN) for the classification of waste images into two categories: organic and recyclable. The primary objective is to leverage machine learning to enhance waste management practices.

## Dataset Overview

The dataset employed in this project comprises images representing both organic and recyclable waste. It is organized into two main sections: TRAIN and TEST. Each section is further divided into subfolders "O" (organic waste images) and "R" (recyclable waste images), providing a labeled dataset for model training and evaluation.

### Dataset Structure

- DATASET
  - TRAIN
    - O (organic waste images)
    - R (recyclable waste images)
  - TEST
    - O (organic waste images)
    - R (recyclable waste images)

## Parts of the Notebook

### Part 1: Importing Libraries and Specifying Dataset Path

This section involves importing essential libraries, such as NumPy, Pandas, Matplotlib, OpenCV, and others. Additionally, the dataset paths for training and testing are defined.

### Part 2: Importing More Useful Libraries

This part includes the importation of further libraries essential for building and training the CNN model.

### Part 3: Loading and Preprocessing the Dataset

In this segment, images from the dataset are loaded and preprocessed, preparing them for input into the CNN model.

### Part 4: Data Exploration and Visualization

Data exploration and visualization are crucial for understanding the dataset. This part involves examining the distribution of classes and visually inspecting random images.

### Part 5: Convolutional Neural Network (CNN) Model

The architecture of the CNN model is defined in this section. This model is designed to learn hierarchical features from the waste images.

### Part 6: Data Generators

Data generators are prepared to facilitate efficient batch processing during model training and testing.

### Part 7: Model Training

This part encompasses the actual training of the CNN model using the specified parameters. Training is conducted on the provided dataset to learn the underlying patterns and features.

### Part 8: Visualizing the Training Process

The training process is visualized by plotting the accuracy and loss over epochs. These visualizations aid in assessing the model's performance and identifying potential issues.

### Part 9: Model Evaluation of Test Data

The trained model is evaluated on the test dataset to assess its generalization capabilities. Performance metrics, such as accuracy, are computed.

## Save the Model

The trained model is saved as "waste_classifier_model.h5" in the /content folder for future use.

## Author

- [zahidparviz](https://github.com/zahidprvz)
