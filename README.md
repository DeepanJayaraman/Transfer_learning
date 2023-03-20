# Transfer_learning
Image classification using transfer learning

This code trains a transfer learning model for image classification using the MobileNet V2 architecture. It first loads the MobileNet V2 model from TensorFlow Hub and sets a predefined layer for transfer learning. It then loads a dataset of cat and dog images from TensorFlow Datasets and resizes them for input into the transfer learning model. The model is compiled with the Adam optimizer and trained for 8 epochs. The accuracy and loss of the model are plotted for both the training and validation sets. 
