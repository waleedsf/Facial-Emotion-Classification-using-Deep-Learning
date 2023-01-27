# Facial-Emotion-Classification-using-Deep-Learning

This project is a facial expression classification model that is trained to recognize different facial expressions in images. The model uses a convolutional neural network (CNN) architecture and is trained on the FER2013 dataset which contains over 35,000 images of faces with 7 different expressions: Angry, Disgusted, Fearful, Happy, Neutral, Sad, and Surprised. The pre-trained model is included in this repository, so you don't have to train your own model.

The model can be used to classify facial expressions in new images, by providing an image as input and it will output the predicted expression.

Dependencies

This project requires python 3, Tensorflow, Numpy, and OpenCV. All dependencies are listed in the requirements.txt file. To install them run pip install -r requirements.txt
Usage:

To test the model, run the test.py file, and provide an image file path as input
To use the model to classify facial expressions in real-time using a webcam, run the webcam.py file.
Note:

The model was trained on FER2013 dataset, So it may not be perfect for other datasets and in some cases the model may misclassify images.
The code is provided as-is and may need further modification to work with other datasets or use cases.
Please let me know if you have any questions or issue
