# Python-class-102


pip install opencv-python

keep the student camera turned off while capturing pic(while running the code)

https://www.geeksforgeeks.org/python-opencv-capture-video-from-camera/


https://www.geeksforgeeks.org/how-to-capture-a-image-from-webcam-in-python/


Python provides various libraries for image and video processing. One of them is OpenCV. OpenCV is a vast library that helps in providing various functions for image and video operations. With OpenCV, we can capture a video from the camera. It lets you create a video capture object which is helpful to capture videos through webcam and then you may perform desired operations on that video.

Steps to capture a video:

Use cv2.VideoCapture() to get a video capture object for the camera.
Set up an infinite while loop and use the read() method to read the frames using the above created object.
Use cv2.imshow() method to show the frames in the video.
Breaks the loop when the user clicks a specific key.
