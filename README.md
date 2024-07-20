# basic_image_processing

`image2pixels.ipynb`
You can change the index value to visualize different images from the training set. This is a useful way to understand and explore the data before training a machine learning model.

`model.ipynb`
This file loads the MNIST dataset, preprocesses the data by normalizing and reshaping it, defines a CNN model, compiles it, trains it on the data, and finally saves the trained model.

`gui.ipynb`
This file creates a web application where users can draw a digit, and the trained model(model.ipynb) predicts the digit. Have used Gradio interface, which provide a user-friendly way to interact with the model without needing any additional setup or configuration.
