This repository contains a Convolutional Neural Network (CNN)-based deep learning project for detecting forest fires from images. It is built using TensorFlow and Keras and trained on The Wildfire Dataset.

Project Structure:

Week 1 Highlights:

Downloaded and extracted The Wildfire Dataset using KaggleHub.

Visualized image samples from the dataset.

Verified GPU availability for accelerated training.

Checked the number of classes (fire, nofire).

Displayed class-wise image samples using Matplotlib.

Week 2 Improvements:

Added image preprocessing using ImageDataGenerator.

Normalized images by rescaling pixel values.

Loaded data in batches of 32 for efficient training.

Enabled shuffling of data to avoid overfitting.

Built a deeper CNN with three Conv2D and MaxPooling2D layers.

Added a Dropout layer to reduce overfitting.

Used binary class mode for classification (fire, nofire).
