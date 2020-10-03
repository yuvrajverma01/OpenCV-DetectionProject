# OpenCV-DetectionProject
 This project was made while I was studying OpenCV for a project with python.
 This documentation can help you to learn Object Detection with OpenCV and Python.
 This project is capable of detecting faces, eyes and both of them from Images, people
 walking and cars moving from Videos and camera.
 
 This was taught by 
 Ilias Papachristos, Data Analyst - Scientist.

 The raw cascades were originally made by:
   Eye Cascade: Stump-based 20x20 by Shameem Hameed
   Face Cascade: Discrete adaboost frontal face detector by Rainer Lienhart

 I am contributing this project to the open source because I want to provide value to my peers.

 Basically, what the source code does is, first it asks the user to what type of detection 
 would the user like to perform? After that, the user is prompted for the input type i.e. either
 a jpg file, mp4 file or the user's camera. Using the haarcascades, the classifiers are trained
 and coded. Detailed description of Source Code is done below:
 
 RoadMap of training the model through a jpg file:
      1. Import Libraries
      2. Create a classifier
      3. Open and fix the image
      4. Detect the object (.detectMultiScale)
      5. Highlighting Function
 
 RoadMap of training the model through a mp4 file:
      1. Import Libraries
      2. Create a classifier
      3. Open the video
      4. While loop (Frame by Frame capture)
 
 RoadMap of training the model through source camera:
      1. Import Libraries
      2. Create a classifier
      3. Video Capture variable(At t=0)
      4. Highlighting Function 
      5. While loop (Frame by Frame capture)
Sample output can be 
<img src="https://repository-images.githubusercontent.com/199413683/78bf3f00-bbcd-11e9-9704-2134ae6fe3f2" width=1000>
