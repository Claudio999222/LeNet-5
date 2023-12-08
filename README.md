# LeNet-5 Reproduction Notebook

In this notebook, we aim to reproduce the LeNet-5 architecture proposed by Yann LeCun for handwritten digit recognition. LeNet-5 is a classic Convolutional Neural Network (CNN) architecture that played a pivotal role in the development of deep learning, particularly for image recognition tasks.

## Key Components of LeNet-5:

1. **Convolutional Layers**: LeNet-5 uses convolutional layers to extract spatial hierarchies of features.

2. **Pooling Layers**: Pooling layers are employed to downsample feature maps, reducing dimensionality.

3. **Activation Functions**: Sigmoid and hyperbolic tangent (tanh) activation functions are used in different layers.

4. **Fully Connected Layers**: Dense layers for classification.

5. **Softmax Activation**: The final layer uses softmax activation for multi-class classification.

6. **Model Training**: Utilizing training data to optimize model parameters.

7. **Model Evaluation**: Assessing the model's performance on a separate set of test data.

By reproducing the LeNet-5 architecture, this notebook aims to showcase the structure of a pioneering CNN and its application to handwritten digit recognition, specifically on the MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0 through 9), making it a widely used benchmark in the field of computer vision.
