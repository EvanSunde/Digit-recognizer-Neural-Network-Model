# Digit Recognition

This repository contains code for a digit recognition system using a Convolutional Neural Network (CNN) implemented in TensorFlow.

## Files

- `digit-ocr.ipynb`: This Jupyter notebook contains the code for creating, training, and evaluating the digit recognition model.

- `image-recognition-function.ipynb`: This Jupyter notebook contains the code for loading the trained model and using it to predict the digit in a given image.

- `digit.model/`: This directory contains the saved model after training.

## Requirements to run this Model

- Python 3
- TensorFlow
- OpenCV-python
- Numpy
- Jupyter (optional)

## Usage

1. Run the `digit-ocr.ipynb` notebook to train the model and save it.

2. Run the `image-recognition-function.ipynb` notebook to use the trained model for digit recognition. You need to provide the path to the image you want to recognize in the `imagePath` variable.


## Note

Please make sure to update the `imagePath` variable in `imge-recognition-function.ipynb` with the path to the image you want to recognize.