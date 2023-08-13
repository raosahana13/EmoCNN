# EmoCNN
Emotion Recognition using Convolutional Neural Networks (EmoCNN) is a straightforward project that demonstrates how to perform emotion recognition on images using pre-trained CNNs. The project uses a dataset from Kaggle and can be easily run on Google Colab or Jupyter notebooks.

#Usage
Download the dataset from Kaggle and extract it to a local directory.
Open the emocnn.ipynb notebook using Google Colab or Jupyter Notebook.
Update the dataset_path variable with the path to the extracted dataset folder.
If using Jupyter Notebook, make sure you have the Keras library installed: pip install keras.
Run the notebook cells to load the pre-trained model, preprocess images, and obtain emotion predictions.

#Dataset
The dataset used in this project is sourced from Kaggle and contains labeled images for emotion recognition. The dataset consists of 7 classes in which 3 classes (happy,neutral,sad) are taken 
https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer

#Model Architecture
The model architecture utilizes a pre-trained CNN for feature extraction and emotion prediction. 
Intially 3 convolutional layer CNN model is constructed and tested with different optimisers inorder to find appropriate Optimiser
In the experimentation we conducted, adam worked best for us
Therefore we built a customised model with adam as optimiser

#Contact
For any questions or collaboration opportunities, feel free to reach out at raosahana13@gmail.com






