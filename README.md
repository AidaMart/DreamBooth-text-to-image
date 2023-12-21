# DreamBooth-text-to-image

Welcome to the Computer Vision Final Project Repository!

In this project, we leveraged the power of the Stable Diffusion pre-trained model and fine-tuned it using DreamBooth to create a Text-to-Image model. Our focus was on generating captivating images based on textual input, particularly using training images of Rapunzel.

## Usage Guide

To facilitate your use of the provided code, we've included a detailed guide. Due to the heavyweight nature of the model, it isn't included in the repository. To fine-tune and train the model, follow these steps:

1. Create an empty folder named `class_data` within the `Data` folder. The program will generate images in this folder during training.
2. Add a folder named `model` within the `Code` folder.

For those without a GPU, we recommend opening `FinetuneDreamBooth.ipynb` with Google Colab to train the model efficiently. The trained model will be saved for future use.

To generate images using the trained model, use `inference.py`. Check the `results` folder to explore the outcomes of our trained model.

Happy exploring and experimenting with the Text-to-Image generation capabilities of our project!
