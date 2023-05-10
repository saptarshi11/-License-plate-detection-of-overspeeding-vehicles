# -License-plate-detection-of-overspeeding-vehicles
The main objective of this project is to identify overspeed vehicles, 
using Deep Learning and Machine Learning Algorithms. After acquisition of series of images from the video, 
trucks are detected using Haar Cascade Classifier. The model for the classifier is trained using lots of positive and negative images to make an XML file.
This is followed by tracking down the vehicles and estimating their speeds with the help of their respective locations, ppm (pixels per meter) and fps (frames per second).
Now, the cropped images of the identified trucks are sent for License Plate detection. The CCA (Connected Component Analysis) assists in Number Plate detection and Characters Segmentation.
The SVC model is trained using characters images (20X20) and to increase the accuracy, 4 cross fold validation (Machine Learning) is also done.
This model aids in recognizing the segmented characters. 
Hardware Requirements:
● Camera: High-resolution cameras are necessary to take clear pictures of the vehicle
speed and license plates. To capture various views, several cameras might be
employed.
● Computer: To process the pictures and data that the cameras have taken, a computer
or server is needed. A powerful processor, adequate memory, and a quick graphics
card are required for image processing on the computer.
● Network Networking: In order to connect all of the system's components, a network
switch and router may be needed.

<pr>To run License-plate-detection-of-overspeeding-vehicles.py, follow these steps below:<br>

Download IDLE python from this site: 'https://www.python.org/downloads/'
Install OpenCV and dlib libraries from: 'https://www.learnopencv.com/install-dlib-on-windows/'
Install these other libraries as well: skimage, sklearn, openpyxl, threading, time, joblib, numpy, matplotlib, datetime, & os.
Through Command Prompt, run this code. (Make sure to change the directories)

 Software Requirements:
● Operating system: A current operating system, like Windows, Linux or MacOS
should be used on the computer.
● Software for Image Processing: To process and examine the images that the cameras
have collected, an image processing software library is needed. We have used
OpenCV.
● Programming Language: The software and methods for overspeed detection and
license plate identification must be implemented using a programming language.
Here, we have used Python.
● Other libraries: dlib, numpy, threading, time and math
