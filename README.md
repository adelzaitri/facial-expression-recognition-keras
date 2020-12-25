# Facial Expression Recognition For Images and Videos with Keras, Tensorflow and Flask

Goals:
======
* Develop a facial expression recognition model in Keras
* Build and train a convolutional neural network (CNN)
* Deploy the trained model to a web interface with Flask
* Apply the model to real-time video streams and image data

Project Steps:
======
1.Introduction and Overview
2.Explore the Dataset
3.Generate Training and Validation Batches
4.Create a Convolutional Neural Network (CNN) Model
5.Train and Evaluate Model
6.Save and Serialize Model as JSON String
7.Create a Flask App to Serve Predictions
8.Create a Class to Output Model Predictions
9.Design an HTML Template for the Flask App
10.Use Model to Recognize Facial Expressions in Videos

Data Sample:
=====

![Data Sample](/read-me-img/facial-express-data-example.png)

Convolutional Neural Network Model Details:
========
![CNN Model](/read-me-img/cnn.jpg)

Model Evaluation:
====
![accuracy of training and validation](/read-me-img/training-evaluation.jpg)


Running the project locally
======

To run the project.<br>
Run:
```python main.py``` <br>
The main script will then run the flask app in the web browser at the port 5000 <br>
#### localhost:5000

To get the program to capture your camera feed, change the ```self.video``` value in the file ```video.py``` as folllows: <br>
```self.video = cv2.VideoCapture(0) #if you put (0) as argument then expression from webcam would be taken```
