# Project
The requirement for this Python project is a webcam through which we will capture images. You need to have Python (3.6 version recommended) installed on your system, then using pip, you can install the necessary packages.

OpenCV – pip install opencv-python (face and eye detection).
TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).
Keras – pip install keras (to build our classification model).
Pygame – pip install pygame (to play alarm sound).


The “haar cascade files” folder consists of the xml files that are needed to detect objects from the image. In our case, we are detecting the face and eyes of the person.
The models folder contains our model file “cnnCat2.h5” which was trained on convolutional neural networks.
We have an audio clip “alarm.wav” which is played when the person is feeling drowsy.
“Model.py” file contains the program through which we built our classification model by training on our dataset. You could see the implementation of convolutional neural network in this file.
“Drowsiness detection.py” is the main file of our project. To start the detection procedure, we have to run this file.
