# Computer Vision Project 2 - Object Detection with Transfer Learning

## Overview
This project involves the implementation of a deep learning model for classifying chest X-ray images into three categories: Normal, Viral Pneumonia, and Covid. The model utilizes transfer learning with the InceptionV3 architecture and is trained on a dataset containing images from these categories. 

## Project Structure
The project consists of several steps, each contributing to the development and evaluation of the deep learning model. Here's a brief overview of each step:

1. **Import Necessary Libraries**: Importing essential libraries for data manipulation, visualization, machine learning, and deep learning.
2. **Set Random Seeds**: Setting random seeds for reproducibility in TensorFlow.
3. **Import Keras ImageDataGenerator**: Importing the ImageDataGenerator class from Keras for data augmentation and preprocessing.
4. **Define Image Dimensions and Batch Size**: Defining image dimensions and batch size for data generators.
5. **Generate Data Using flow_from_directory**: Creating data generators for training and testing data.
6. **Print the Distribution of Classes**: Calculating and printing the distribution of classes in the dataset.
7. **Function to Plot Sample Images**: Defining a function to plot sample images from the data generator.
8. **Plot Sample Images**: Plotting sample images from the training data generator.
9. **Clear the Keras Session**: Clearing the Keras session to release resources.
10. **Import a Pre-trained Model (InceptionV3)**: Importing the InceptionV3 model for transfer learning.
11. **Create a Base Model Using InceptionV3**: Creating a base model using InceptionV3 with pre-trained weights.
12. **Create the Model for Classification**: Constructing the classification model by adding custom layers on top of the InceptionV3 base model.
13. **Compile the Model**: Compiling the model with specified loss function, optimizer, and evaluation metrics.
14. **Define Callbacks for Model Training**: Defining callbacks for model training, including model checkpointing, early stopping, and learning rate scheduling.
15. **Train the Model with Various Batch Sizes and Early Stopping**: Training the model with data generators for various batch sizes and early stopping.
16. **Plot the Learning Curve**: Visualizing the training and validation accuracy and loss over epochs.
17. **Evaluate the Model on Training and Testing Data**: Evaluating the model on both training and testing data and displaying the results.
18. **Evaluate the Model on the Test Data and Generate Predictions**: Evaluating the model on the test data and generating predictions.
19. **Plot Confusion Matrix and Classification Report**: Plotting the confusion matrix and displaying the classification report.

## How to Use
1. **Data Preparation**: Ensure that your dataset is organized in the directory structure expected by the `flow_from_directory` method of Keras.
2. **Environment Setup**: Set up your Python environment with the necessary libraries as specified in the code.
3. **Code Execution**: Execute each step of the provided code in sequential order.
4. **Model Training**: Train the model using the specified parameters, and monitor the training process using the learning curve plot and model checkpoints.
5. **Evaluation**: Evaluate the trained model on both training and testing data to assess its performance.
6. **Prediction**: Generate predictions on new data using the trained model and analyze the results using the confusion matrix and classification report.

## Conclusion
This project demonstrates the implementation of a deep learning model for classifying chest X-ray images into different disease categories. By leveraging transfer learning with the InceptionV3 architecture and applying appropriate training techniques, the model achieves significant accuracy in distinguishing between Normal, Viral Pneumonia, and Covid cases. Further optimizations and fine-tuning can be explored to improve the model's performance even further.