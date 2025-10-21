Cat and Dog Image Classification using CNN

A Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify images of cats and dogs.
This project demonstrates the use of deep learning for binary image classification and computer vision applications.

#Overview
This project trains a CNN model to distinguish between cats and dogs from a labeled image dataset.
The dataset contains over 2000 training images and 400 test images.
The model learns visual patterns through convolution and pooling layers, achieving strong classification accuracy.

#Technologies Used
->Python
->TensorFlow / Keras
->NumPy
->Matplotlib
->Google Colab

#Model Architecture
Input Layer: 100×100 RGB images
Conv2D Layer 1: 32 filters, 3×3 kernel, ReLU activation
MaxPooling2D Layer 1: 2×2 pool size
Conv2D Layer 2: 32 filters, 3×3 kernel, ReLU activation
MaxPooling2D Layer 2: 2×2 pool size
Flatten Layer
Dense Layer: 64 neurons, ReLU activation
Output Layer: 1 neuron, Sigmoid activation
Loss Function: Binary Crossentropy
Optimizer: Adam
Metric: Accuracy

#Results
->Trained a CNN model capable of classifying cat and dog images with high accuracy
->Evaluated model performance on unseen data
->Visualized predictions using Matplotlib to verify results
