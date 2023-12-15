# CNN-ImageClassifier
This is a project that uses TensorFlow and Keras to build a simple image classifier that can distinguish between happy and sad faces. The project uses a custom dataset of 262 images, which are normalized and split into train, validation, and test sets. The model is a convolutional neural network with three convolutional layers, a dropout layer, a flatten layer, and two dense layers. The model is trained on Google Colab using a TPU strategy for faster computation.

# Requirements
To run this project, you need the following packages:

TensorFlow 2.15.0
Matplotlib 3.7.1
OpenCV 4.8.0.76
You can install them using the following command:
```bash
!pip install tensorflow matplotlib opencv-python
````

# Usage
To use this project, you need to upload the data folder to your Google Colab session storage. The data folder contains two subfolders: happy and sad, which contain the images of happy and sad faces respectively. You also need to upload the imageClassifier.ipynb notebook to your Google Colab session.

Then, you can run the cells in the notebook to load the data, build the model, train the model, and evaluate the model on the test set. You can also use the model to make predictions on new images by uploading them to the session storage and using the cv2.imread function to read them.

# Results
The model achieves an accuracy of 0.9688 on the test set, which means it can correctly classify 31 out of 32 images.
