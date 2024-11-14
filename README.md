# Real-Time Emotion Detection Using Facial Recognition
This project is a real-time emotion detection system using Convolutional Neural Networks (CNNs) and OpenCV. The model detects and classifies human facial expressions into various emotion categories such as happy, sad, angry, and more.
Model architecture saved in JSON format and weights saved in H5 format

# Seven emotion categories:
Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise


# Dataset Link: 
https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset
The model was trained on an open-source dataset of facial images labeled with emotion categories. Each image was preprocessed to grayscale and resized to 48x48 pixels.


# To install the required packages:

pip install -r requirements.txt

Clone this repository:
git clone https://github.com/Navartna/Emotion-Recognition-Machine-Learning.git
Download the pre-trained model files: emotiondetector.json and emotiondetector.h5, and place them in the project directory.

To retrain the model or improve accuracy, you can use the code provided in train_model.py. The model is trained using the Keras fit function, with callbacks for early stopping and learning rate reduction.


# Accuracy: 
Achieved approximately 71% accuracy on initial training.
