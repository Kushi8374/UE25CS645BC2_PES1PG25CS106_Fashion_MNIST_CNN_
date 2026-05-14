# UE25CS645BC2_PES1PG25CS106_Fashion_MNIST_CNN_
# Introduction

Convolutional Neural Networks (CNNs) are one of the most important deep learning architectures used in computer vision tasks such as image classification, object detection, facial recognition, and pattern recognition.

CNNs automatically learn features from images using operations like convolution and pooling. In this project, a CNN model is implemented completely from scratch using NumPy without using advanced deep learning frameworks such as TensorFlow or PyTorch.

The model is trained and evaluated on the Fashion MNIST dataset using Google Colab.

# Objective of the Project

The objectives of this project are:

- To understand the working of Convolutional Neural Networks
- To implement convolution operation manually
- To implement forward propagation
- To implement backward propagation
- To implement MaxPooling operation
- To build a Fully Connected Layer
- To train the CNN model on image data
- To evaluate the CNN model performance

# Development Environment

This project was implemented and executed using:

- Google Colab
- Python
- NumPy
- Matplotlib
- Keras Dataset Loader
- tqdm


# About Fashion MNIST Dataset

Fashion MNIST is a dataset of grayscale clothing images used for image classification tasks.

Dataset Details:
- 70,000 grayscale images
- 60,000 training images
- 10,000 testing images
- 10 classes
- Image size: 28 × 28 pixels


# Dataset Classes

| Label | Class Name |
|---|---|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

# CNN Architecture

```txt
Input Image (28×28)
        ↓
Convolution Layer
        ↓
ReLU Activation
        ↓
MaxPooling Layer
        ↓
Flatten Layer
        ↓
Fully Connected Layer
        ↓
Softmax Output Layer
```

# Convolution Layer

The convolution layer extracts important image features such as edges, shapes, and textures using filters (kernels).

The filters slide over the image and perform mathematical convolution operations.

Advantages:
- Feature extraction
- Parameter sharing
- Efficient image processing


# ReLU Activation Function

ReLU (Rectified Linear Unit) introduces non-linearity into the CNN model.

Formula:

```txt
ReLU(x) = max(0, x)
```

Benefits:
- Faster training
- Removes negative values
- Helps deep learning models learn complex patterns

# MaxPooling Layer

MaxPooling reduces feature map dimensions while preserving important information.

In this project:
- 2×2 MaxPooling is used

Advantages:
- Reduces computation
- Reduces overfitting
- Speeds up training

# Fully Connected Layer

The Fully Connected Layer performs classification using extracted features.

Softmax activation is used to generate probability scores for each class.

# Softmax Activation Function

Softmax converts outputs into probabilities.

Formula:

```txt
Softmax(xi) = e^xi / Σ(e^xj)
```

Properties:
- Values range between 0 and 1
- Total probability equals 1

# Forward Propagation

Forward propagation is the process where input images pass through all CNN layers to produce predictions.

Steps:
1. Convolution
2. ReLU Activation
3. MaxPooling
4. Flattening
5. Fully Connected Layer
6. Softmax Prediction

# Backward Propagation

Backward propagation calculates gradients and updates weights using gradient descent.

Purpose:
- Reduce prediction error
- Improve model accuracy
- Optimize CNN parameters

Weight Update Formula:

```txt
New Weight = Old Weight − Learning Rate × Gradient
```


# Training Process

The CNN model is trained using:
- Forward propagation
- Loss calculation
- Backpropagation
- Weight updates

The training is performed for multiple epochs to improve performance.


# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| NumPy | Mathematical operations |
| Matplotlib | Graph plotting |
| Keras | Dataset loading |
| tqdm | Progress bar |
| Google Colab | Development environment |


# Google Colab Execution

The complete project was executed in Google Colab.

Advantages of using Google Colab:
- Free cloud environment
- No installation required
- Easy execution of Python notebooks
- Supports machine learning workflows


# Installation

Install required libraries:

```bash
pip install numpy matplotlib keras tqdm
```


# How to Run the Project

Open the notebook in Google Colab and run all cells sequentially.

# Output

The program displays:
- Dataset information
- Training progress
- Training loss
- Training accuracy
- Test accuracy
- Accuracy graph
- Loss graph

# Example Output:

```txt
Epoch 1
Average Loss: 1.24
Accuracy: 76.32%

Epoch 2
Average Loss: 0.82
Accuracy: 84.10%

Test Accuracy: 82.45%
```

# Accuracy Graph

The training accuracy graph shows improvement in CNN performance during training.

(Add screenshot here)


# Loss Graph

The loss graph shows reduction in training loss during learning.

(Add screenshot here)


# Advantages of CNN

- Automatic feature extraction
- Efficient image classification
- Reduced parameters
- High accuracy
- Better handling of image data


# Applications of CNN

CNNs are used in:
- Image classification
- Object detection
- Face recognition
- Medical imaging
- Autonomous vehicles
- Security systems


# Learning Outcomes

This project helped in understanding:
- CNN architecture
- Convolution operation
- Pooling operation
- Activation functions
- Forward propagation
- Backpropagation
- Gradient descent
- Image classification concepts


# Conclusion

This project successfully implemented a Convolutional Neural Network from scratch using NumPy and trained it on the Fashion MNIST dataset.

The project provided a deeper understanding of CNN internals including convolution, pooling, activation functions, forward propagation, and backpropagation.

The model achieved good classification accuracy and demonstrated the effectiveness of CNNs in image classification tasks.

 here.
