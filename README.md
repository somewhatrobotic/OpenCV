��# OpenCV

**Scripts currently being worked on**
Tracker_and_depth_Measure.py
Goal: To read live video stream and identify person, show position relative to OAK-D, depth etc.
Ever 10 seconds a photo is recorded of a detected person



Currently working on Face_Detection_v1.py
Goal: To read User_ID images and record facial features. Take those features and build a classifer, reimplement classifer into live video stream

To be created:
Tracker + Face Detection.py

After 10-15 photos have been taken of the same User_ID, classifier is created for face.
User request to name classifier(name of person)
After user input, Tracker is restarted with new updated classifier. 
Photo taking occurs every minute now. Wait for addition 10-15 photos to reupdate classifer.

