# Neural Network Implementation from Scratch

## Generative AI Lab – Practice Assignment 1

This project implements a simple feedforward neural network from scratch in Python for handwritten digit classification using the MNIST dataset.

The neural network is implemented using NumPy without using built-in deep learning frameworks such as TensorFlow, PyTorch, or Keras.

## Objective

The main objective of this assignment is to understand how a neural network works internally by implementing its basic components manually.

The implementation includes:

* Forward propagation
* ReLU and Softmax activation functions
* Cross-entropy loss
* Backpropagation
* Gradient descent
* Mini-batch training
* Model evaluation
* Result visualization

## Dataset

The MNIST dataset contains grayscale images of handwritten digits from 0 to 9.

* Training images: 60,000
* Testing images: 10,000
* Image size: 28 × 28 pixels
* Input features: 784
* Number of classes: 10

The dataset is downloaded from Kaggle using KaggleHub.

## Neural Network Architecture

The network used in this project is:

```text
784 Input Neurons
        ↓
128 Neurons + ReLU
        ↓
64 Neurons + ReLU
        ↓
10 Neurons + Softmax
```

The 784 input values represent the pixels of a 28 × 28 image.

The 10 output neurons represent the digits from 0 to 9.

## Implementation

The project follows these steps:

1. Load the MNIST dataset.
2. Explore the dataset and visualize sample images.
3. Separate images and labels.
4. Normalize pixel values from 0–255 to 0–1.
5. Convert labels into one-hot encoded vectors.
6. Initialize weights using He initialization.
7. Perform forward propagation.
8. Calculate cross-entropy loss.
9. Perform backpropagation to calculate gradients.
10. Update weights and biases using gradient descent.
11. Train the network using mini-batches.
12. Evaluate the model on the test dataset.
13. Visualize training results and sample predictions.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Google Colab
* KaggleHub

## Project Files

```text
Neural-Network-From-Scratch-MNIST/
│
├── Swapnil_Akhade_GenerativeAILabAssignment.ipynb
├── README.md
└── results/
    ├── loss_graph.png
    ├── accuracy_graph.png
    ├── predictions.png
    ├── training_results.png
    ├── testing_results.png
    └── class_distribution.png
```

## Results

The model is trained on the complete MNIST training dataset and evaluated using the 10,000 test images.

The notebook contains:

* Training loss graph
* Training accuracy graph
* MNIST class distribution
* Sample digit predictions
* Test loss and test accuracy

The exact performance results can be viewed in the submitted notebook.

## Conclusion

This project helped in understanding the basic working of a neural network by implementing the important steps manually. The network was able to learn patterns from handwritten digit images and classify the MNIST test images.

The assignment demonstrates how forward propagation, loss calculation, backpropagation, and gradient descent work together to train a neural network.

## Author

**Swapnil Santosh Akhade**

CSE AIML
MIT Academy of Engineering, Alandi
