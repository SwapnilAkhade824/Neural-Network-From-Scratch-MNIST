# Model Results

This folder contains the results and visualizations obtained after training the neural network on the MNIST dataset.

## Training Results

The model was trained for 10 epochs using mini-batch gradient descent with a batch size of 64 and a learning rate of 0.01.

* Final Training Loss: **0.1643**
* Final Training Accuracy: **95.56%**

![Training Results](training_results.png)

## Testing Results

After training, the model was tested on the 10,000 MNIST test images.

* Test Loss: **0.1607**
* Test Accuracy: **95.29%**

![Testing Results](testing_results.png)

## Loss Graph

The training loss decreases from **0.7958** in the first epoch to **0.1643** in the tenth epoch. This shows that the model gradually improved its predictions during training.

![Training Loss](loss_graph.png)

## Accuracy Graph

The training accuracy increases from **88.52%** in the first epoch to **95.56%** in the tenth epoch.

![Training Accuracy](accuracy_graph.png)

## Sample Predictions

The model was tested on sample MNIST images. The predicted digit and actual digit are shown for each image.

The displayed examples were correctly classified by the model.

![Sample Predictions](predictions.png)

## Class Distribution

This graph shows the number of training images available for each digit from 0 to 9.

![Class Distribution](class_distribution.png)

## Summary

The neural network achieved **95.29% accuracy on the MNIST test dataset** after training for 10 epochs. The close training and testing accuracy indicates that the model performed consistently on both training and unseen test data.
