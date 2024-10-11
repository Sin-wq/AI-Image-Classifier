# AI Image Classifier

The objective of the project is to build a custom deep image
classifier that can be used to classify any images based on binary
classification. The scope of the project is limited to building the
classifier and evaluating its performance on a small dataset of
images.


## Methodology

- Imagine you want to teach a computer to recognize different types of animals, such as cats, dogs, and birds. You need to give the computer a lot of examples of each animal, so it can learn how they look. These examples are called data.
- The data needs to be organized and prepared before the computer can use it. For example, you need to resize the images to the same size, split the data into training and testing sets, and label each image with the correct animal name. This process is called data pipeline and data preprocessing.
- The computer needs a way to process the data and make predictions. For this, you need to design a deep neural network, which is a series of mathematical operations that transform the images into numbers. The network has many layers, each with a specific function. Some layers are called convolutional layers, which detect patterns and features in the images. Other layers are called pooling layers, which reduce the size and complexity of the data. The last layer is called the output layer, which gives the final prediction of the animal type.
- The network needs to be trained and evaluated to see how well it performs. For this, you need to use a loss function, which measures the difference between the network’s prediction and the actual label. You also need to use an optimizer, which adjusts the network’s parameters to minimize the loss. You can plot the loss and accuracy over time to see the network’s performance. This process is called model evaluation.
- The network needs to be saved and loaded for future use. For this, you need to use a file format, such as h5, which stores the network’s structure and parameters. You can also use the network to make predictions on new images that it has not seen before. This process is called model saving and model testing.
