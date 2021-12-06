Project Title: Sleepy Driver Detection

Project Description: 

To alert the monitoring system about the sleepy drivers using camera. 
It gives the status of driver instantly if he is in active or sleepy condition.

Application: To avoid road accidents, which are mostly due to sleepy drivers.

This project built is using Dlib and OpenCV with Python language.
The 68-landmark detector data (.dat) file can be found using below link:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Logic of project:

The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. 
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using 
which we determine whether the eyes are open or they are closed.

The working of the project
Here the facial landmarks are detected using the detector.
Then, we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance 
between horizontal landmarks.