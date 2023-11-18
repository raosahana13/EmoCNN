# EmoCNN - Emotion Recognition using Convolutional Neural Networks

EmoCNN is a straightforward project demonstrating how to perform emotion recognition on images using pre-trained Convolutional Neural Networks (CNNs). The project utilizes a dataset from Kaggle and can be easily run on Google Colab or Jupyter notebooks.

## Usage

1. Download the dataset from Kaggle
2. Extract the dataset to a local directory.
3. Open notebook using Google Colab or Jupyter Notebook.
4. Update the `dataset_path` variable with the path to the extracted dataset folder.
5. If using Jupyter Notebook, ensure you have the Keras library installed: `pip install keras`.
6. Run the notebook cells to load the pre-trained model, preprocess images, and obtain emotion predictions.

## Dataset

The dataset used in this project is sourced from Kaggle and contains labeled images for emotion recognition. It consists of 7 classes, and for this project, I focus on 3 classes: happy, neutral, and sad.

Dataset Link: [Emotion Detection FER Dataset](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer)

## Model Architecture

The model architecture utilizes a pre-trained CNN for feature extraction and emotion prediction. Initially, a 3-convolutional-layer CNN model is constructed and tested with different optimizers to find the most suitable one. In our experimentation, Adam worked best, so we built a customized model with Adam as the optimizer.

## Notebooks

1. `variousmodel.ipynb`: Compares model behavior on different optimizers.
2. `customisedmodel.ipynb`: Customized model testing on test images and Grad-CAM as explainability.

