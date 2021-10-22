# Face-Mask-Detection
Real-Time Face Mask Detection System  using Deep Learning and OpenCV


About Project

This project uses a Deep Neural Network, more specifically
a Convolutional Neural Network, to differentiate between images
of people with and without masks. The CNN manages to get an accuracy of 98.2% on
the training set and 97.3% on the test set. Then the stored weights of this CNN are used
to classify as mask or no mask, in real time, using OpenCV. With the webcam capturing the video,
the frames are preprocessed and and fed to the model to accomplish this task. 
The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

The model is capable of predicting multiple faces with or without masks at the same time


Testing The Model in Real-Time


To test our model in real-time, I’ll be using the VideoCapture function
in the OpenCV library in Python. The Cascade classifier, designed by OpenCV,
was used to detect the frontal face in live video via detectMultiScale.
We can use a while loop to continue capturing images from the webcam.


Our machine learning model will then determine whether or not a face mask is worn in real-time.
Based on the performance and accuracy of our model, the result of the binary classifier will be 
indicated by showing a green rectangle superimposed around the section of the face indicating that the person
at the camera is wearing a mask, or a red rectangle indicating that the person on camera is not wearing a mask.


Thanks:

Amitesh kumar mishra

