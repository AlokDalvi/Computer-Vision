# Computer Vision Project 1 - Object Detection with Transfer Learning

### Overview
This project aims to enhance border security in India using unmanned drones. A model is developed to detect various objects in images captured by these drones. The objects include airplanes, automobiles, birds, cats, deers, dogs, frogs, horses, ships, and trucks.

### Steps
1. **Import Libraries**: Necessary libraries like TensorFlow, Keras, Matplotlib, and NumPy are imported.
2. **Define Object Classes**: A list of classes representing objects to be detected is defined.
3. **Load and Normalize CIFAR-10 Dataset**: The CIFAR-10 dataset is loaded and pixel values are normalized to [0, 1].
4. **Load Pre-trained VGG16 Model**: A pre-trained VGG16 model with ImageNet weights is loaded.
5. **Add Custom Layers for Classification**: Custom layers are added for final classification.
6. **Create the Final Model**: The model is created by combining the base VGG16 model with custom layers.
7. **Compile the Model**: The model is compiled with specified optimizer, loss function, and metrics.
8. **Display Model Summary**: Summary of the model architecture is displayed.
9. **Implement Early Stopping**: Early stopping is implemented to monitor validation loss and restore best model weights.
10. **Train the Model**: The model is trained with specified data, epochs, and early stopping.
11. **Plot Training History**: Training and validation accuracy and loss across epochs are plotted.
12. **Evaluate the Model on Test Data**: The model is evaluated on test data and test accuracy is printed.
13. **Save the Trained Model**: The trained model is saved to a file.
14. **Define Function to Display Sample Predictions**: A function is defined to display sample images and their predictions.
15. **Display Multiple Sample Predictions**: Multiple sample predictions are displayed using the defined function.
16. **Load the Trained Model and Define Functions for Prediction**: The saved model is loaded and functions are defined for image preprocessing and prediction.
17. **Make Predictions and Display Results for Uploaded Photos**: The defined functions are used to make predictions and display results for uploaded photos.

### Usage
1. **Train the Model**: Execute the provided code to train the model with the CIFAR-10 dataset.
2. **Save the Trained Model**: Save the trained model to a file for future use.
3. **Predict on Uploaded Photos**: Use the provided functions to predict on new images and display the results.

### Dependencies
- TensorFlow
- Keras
- Matplotlib
- NumPy
- CIFAR-10 Dataset

### License
This code is licensed under the MIT License.

### Disclaimer
This project is for educational and research purposes only. It does not replace professional advice or judgment. Please consult professionals before making any decisions based on the results obtained from the model.