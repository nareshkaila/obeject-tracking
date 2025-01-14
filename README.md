# obeject-tracking

Object Tracking with OpenCV and TensorFlow
This repository demonstrates how to integrate object detection and object tracking using a pre-trained MobileNet SSD model with TensorFlow and OpenCV. The system first detects objects in a video using the object detection model and then tracks those objects across subsequent frames using OpenCV’s tracking algorithms.

Key Features:
Object Detection: Uses TensorFlow’s MobileNet SSD, a fast and efficient deep learning model, to detect common objects such as people, cars, and bicycles in real-time.
Object Tracking: After detecting an object, a tracker (e.g., TrackerCSRT) is initialized to track the object across subsequent video frames.
Real-Time Video Processing: The system continuously processes video frames and updates the object’s position, drawing bounding boxes around the tracked object.
Requirements
To run the project, you will need the following libraries:

TensorFlow 2.x: For object detection using a pre-trained MobileNet SSD model.
OpenCV: For image and video processing, including object tracking.
