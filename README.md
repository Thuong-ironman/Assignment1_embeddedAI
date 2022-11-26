# Assignment1_embeddedAI
In this assignment, you will use both traditional methods and modern deep learning methods to detect objects in a scene.
Problem 1: Traditional Object Detection

    Find an image containing an object in a cluttered scene (call this image the test image).
    Use OpenCV to extract the object from the image above, and save it to the file system as a new image (call this image the template image).
    Apply object recognition based on SIFT or SURF local features and descriptors matching offered by the OpenCV library, to find the template in the test image (hint: https://docs.opencv.org/4.6.0/dc/dc3/tutorial_py_matcher.html 

    Links to an external site.).

Problem 2: Deep Learning Based Object Detection

    Find an image that contains multiple people (more than 4 preferably).
    Write an algorithm (some code) that counts the number of people in the image, using a pre-trained deep learning-based object detection model (e.g. MobileNet SSD or YOLO). These models have been trained to recognize many different classes, including the class "Person".
    Use OpenCV to display the number of people in the image, by drawing some text on the image.
    Also, draw a bounding box around each detected person.

