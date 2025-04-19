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

Week 3 Enhancements:

Compiled the CNN model using Adam optimizer and binary cross-entropy loss.

Trained the model for 12 epochs with validation.

Plotted training and validation accuracy and loss curves.

Evaluated model performance using the test set.

Saved the trained model (FFD.keras).

Created a predict_fire() function to classify new images as fire or nofire.

Requirements:

Python 3.x

TensorFlow 2.x

Matplotlib

NumPy

KaggleHub

Future Enhancements:

Add data augmentation (rotation, zoom, flip).

Implement early stopping and model checkpoints.

Use transfer learning with a pre-trained model like ResNet or EfficientNet.

Visualize confusion matrix and classification report.
