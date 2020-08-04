# Project-Handwritten-Digit-Recognition
The hello world of object recognition for machine learning and deep learning

Architecture of CNN model
1. The first hidden layer is a convolutional layer called a Convolution2D. The layer has 32
feature maps, which with the size of 5 ⇥ 5 and a rectifier activation function. This is the
input layer, expecting images with the structure outline above.
2. Next we define a pooling layer that takes the maximum value called MaxPooling2D. It is
configured with a pool size of 2*2.
3. The next layer is a regularization layer using dropout called Dropout. It is configured to
randomly exclude 20% of neurons in the layer in order to reduce overfitting.
4. Next is a layer that converts the 2D matrix data to a vector called Flatten. It allows the
output to be processed by standard fully connected layers.
5. Next a fully connected layer with 128 neurons and rectifier activation function is used.
6. Finally, the output layer has 10 neurons for the 10 classes and a softmax activation function
to output probability-like predictions for each class.
