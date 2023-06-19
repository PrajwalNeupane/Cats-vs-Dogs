# Cats-vs-Dogs

This repository contains a Convolutional Neural Network (CNN) based Image Classifier that accurately distinguishes between cat and dog images.

## Features
- Utilizes a deep learning model (CNN) for image classification
- Trained on a large dataset of cat and dog images
- Achieves high accuracy on validation dataset

## Installation

### Windows

Install the required dependencies using the `requirements.txt` file with the following command:

```
pip install -r requirements.txt
```

### Apple Silicon

To install TensorFlow, follow the tutorial at:

https://www.tensorflow.org/install/pip

Remove 'tensorflow==2.7.0' from `requirements.txt` and then install the remaining dependencies using the same command as for Windows:

```
pip install -r requirements.txt
```

## Data Preparation

1. Download the dataset zip file from:

https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765

2. Extract the `PetImages` folder from the zip file and place it inside the `tmp` (you need to create the directory) directory in the project folder.

## Usage

1. Place the images you want to classify into the `tmp/test` folder.
2. Open the `main.ipynb` file in a Jupyter Notebook.
3. Run all the cells in the notebook.
4. The classification results will be displayed as output in the notebook.

## Performance

The model has been trained on a dataset containing thousands of cat and dog images. It achieved an accuracy of *89.91%* during training and *83.00%* on the validation dataset. Please note that the classification accuracy may vary depending on the quality and variety of images used for testing.

## Acknowledgments

This project is based on the Cats-vs-Dogs image classification problem from the Kaggle competition (https://www.kaggle.com/c/dogs-vs-cats).