# Predict-the-Rice-Leaf-Disease-using-CNN
Created a model to detect Rice rice leaf pest detection Using Neural Network using Functional API to create a model like tensor flow, Used CNN for image classification and its hyper parameter
CNN
Project Description
This project aims to classify rice leaf diseases using a Convolutional Neural Network (CNN). The model is trained on a dataset of rice leaf images labeled with different disease categories. The project encompasses various stages including data preprocessing, model creation, training, evaluation, and visualization of results.

Table of Contents
Installation
Usage
Dataset
Model Architecture
Training
Evaluation and Testing
Visualization
Contributing
License
Installation
To set up the necessary environment to run this project:

Clone the repository to your local machine.
Install the necessary packages using the following command:
Copy code
pip install -r requirements.txt
Ensure you have TensorFlow and Keras installed in your Python environment.
Usage
Provide instructions on how to use your project. Include code snippets, examples, etc.

Dataset
The dataset consists of images of rice leaves categorized into different disease types. The data is split into training, validation, and test sets. Data augmentation is applied to increase the diversity of the training dataset.

Model Architecture
The CNN model is built using Keras and consists of several layers including convolutional layers, max-pooling layers, and dense layers. The model architecture is detailed in the script.

Training
The model is trained using the Adam optimizer and categorical cross-entropy loss function. Training accuracy and loss are plotted over epochs to visualize the training process.

Evaluation and Testing
After training, the model is evaluated on a test set to determine its performance. The evaluation metrics include loss and accuracy.

Visualization
The script includes code to visualize training images and the predictions of the model on test images.
