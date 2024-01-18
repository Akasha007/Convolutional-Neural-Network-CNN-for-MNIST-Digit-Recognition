Convolutional Neural Network (CNN) for MNIST Digit Recognition
This repository contains a Python notebook that implements a Convolutional Neural Network (CNN) to predict digits from images in the MNIST dataset. The notebook follows a structured workflow covering architecture design, data preprocessing, model building, training, testing, and result visualization.

Workflow
Architecture
The CNN architecture is designed as follows:

Convolutional layer with 50 filters, kernel size of 5, and ReLU activation
Maxpooling layer with a pool size of (2,2)
Convolutional layer with 50 filters, kernel size of 3, and ReLU activation
Maxpooling layer with a pool size of (2,2)
Flattening layer
Dense layer with 10 units (output probabilities)
Preprocessing the Data
The dataset is preprocessed through scaling, splitting, and batching. Key steps include:

Scaling pixel values to the range [0, 1]
Splitting the dataset into training, validation, and test sets
Batching the datasets for optimal performance
Build and Train the Model
The CNN model is built using TensorFlow's Keras API. It is compiled with the Adam optimizer and Sparse Categorical Crossentropy loss function. Early stopping is implemented to prevent overfitting.

Testing the Model
The trained model is evaluated on the test dataset, providing test loss and accuracy metrics.

Plotting Images and Results
The notebook includes code to visualize individual test images, display correct labels, and show the model's predicted probabilities.

Getting Started
To run the notebook locally, make sure you have TensorFlow and other required libraries installed. Use Jupyter Notebook or a similar environment.
