# Hand Gesture Recognition Model (test acc = 99.3%)
![image](https://github.com/SaadElDine/PRODIGY_ML_04/assets/113860522/16b7efda-2301-4bfb-b390-a141a80c181f)

## Overview
This project aims to develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data. The model enables intuitive human-computer interaction and gesture-based control systems.

## Dataset
The dataset used for training and testing the model is the Sign Language MNIST dataset. This dataset contains images of hand gestures representing the American Sign Language alphabet letters (excluding J and Z, which require motion). Each image is a grayscale 28x28 pixel image, and there are 27,455 training images and 7,172 testing images.

## Model
The model architecture used for this task is a Convolutional Neural Network (CNN). CNNs are well-suited for image classification tasks due to their ability to learn hierarchical features from images.

## Training
The model is trained using the training images from the Sign Language MNIST dataset. The training process involves optimizing the model's parameters to minimize the classification error. The model is trained using the Adam optimizer and categorical crossentropy loss function.

## Evaluation
The trained model is evaluated using the testing images from the Sign Language MNIST dataset. The evaluation metrics used include accuracy, precision, recall, and F1-score. These metrics help assess the model's performance in classifying hand gestures.
![image](https://github.com/SaadElDine/PRODIGY_ML_04/assets/113860522/0fb54710-7c8e-401b-823d-cda009112950)

## Deployment
The trained model can be deployed in real-time applications to classify hand gestures from video or webcam feeds. The model can be integrated into applications that require gesture-based control, such as sign language translation systems or interactive interfaces.
![test case A](https://github.com/SaadElDine/PRODIGY_ML_04/assets/113860522/20ba8774-b301-4d4f-9de4-2bc41d66b7ea)
![test case B](https://github.com/SaadElDine/PRODIGY_ML_04/assets/113860522/5fbe2958-cb5d-4bb8-9da0-2d8fbcbcf38f)


## Conclusion
Developing a hand gesture recognition model has the potential to improve human-computer interaction and accessibility for individuals with hearing impairments. By accurately recognizing and classifying hand gestures, the model can enable more intuitive and efficient communication methods.

