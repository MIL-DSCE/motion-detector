# Motion Detection on the Raspberry Pi using OpenCV and python

This is a motion detector application still in development for the raspberry pi.

The quickstart.py just takes input from the camera and uploads it to google drive.

The Motion_Detection.py shows the motion detected in the form of artficially drawn contours. It saves a local copy of a jpg file. This file is then uploaded and an email is sent to the user telling that the motion is detected. A GUI interface also shows a temporary version of the motion being detected and uploaded.
The entire application is using OpenCV on python to capture the video buffer and then detect the motion. It is using a completely different process to increase the efficiency of the program.
