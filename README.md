# Custom Convolutional Neural Network with TensorFlow

This repository contains a Python implementation of a simple Convolutional Neural Network (CNN) using TensorFlow. The code includes a custom Conv2D layer with a specified 3x3 filter. The CNN is applied to images from the CIFAR-10 dataset, and a separate image ('Mensa.jpg').

## Usage

### Requirements

- Python 3.x
- TensorFlow
- Matplotlib
- Numpy

Install the required dependencies using:

```bash
pip install -r requirements.txt

Running the Code
Run the custom_cnn.py script to train the model and visualize the output.
bash
Copy code
python custom_cnn.py
Check the model summary, original, and filtered images in the generated plots.

Explore the application of the custom filter to the provided image ('Mensa.jpg')

Files
custom_cnn.py: Main script containing the CNN model and application of filters.
requirements.txt: List of required dependencies.
Additional Information
The CNN model uses a custom Conv2D layer with a specified 3x3 filter.
The CIFAR-10 dataset is used for training and testing.
Additional image ('Mensa.jpg') is provided for filter application.
Acknowledgments
This project is based on a tutorial for learning TensorFlow and CNN concepts.

Feel free to explore, modify, and use this code for educational purposes or as a starting point for your projects!
