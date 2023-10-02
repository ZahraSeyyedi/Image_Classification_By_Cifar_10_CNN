
# Image_Classification_By_Cifar_10_CNN


This project aims to classify images from the CIFAR-10 dataset using deep learning techniques. The dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The goal is to classify each image into its corresponding class.
Data set : The CIFAR-10 dataset can be downloaded from the official website, or through the Tensorflow and Keras librares. It is split into a training set of 50,000 images and a test set of 10,000 images. Each image is a 32x32 pixel RGB image, with 3 color channels
Model : In this project, a convolutional neural network (CNN) is used to classify the images. The model consists of 8 convolutional layers. ReLU activation function is used for all the layers except the last layer, which uses a softmax function to produce the output probabilities for each class.

The model was trained on the training set for 200 epochs, with a batch size of 64 . The training process achieved an accuracy of 91.48% and loss of   0.3976 on the test set.
