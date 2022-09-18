# Pose Estimation
Pose estimation is the task of using an ML model to estimate the pose of a person from an image or a video by estimating the spatial locations of key body joints (keypoints).
This is typically done by identifying, locating, and tracking a number of keypoints on a given object or person. For objects, this could be corners or other significant features. And for humans, these keypoints represent major joints like an elbow or knee.

# What is the main idea?
The idea is to move a robotic arm my mimicking the arm movements on a human arm. This can be achieved using pose detection
There are several modules/frameworks which can be used, such as:'

*Mediapipe:* MediaPipe is a Framework for building machine learning pipelines for processing time-series data like video, audio, etc.

*OpenCV:* OpenCV is the huge open-source library for the computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today’s systems.

*TensorFlow:* TensorFlow is a Python-friendly open source library for numerical computation that makes machine learning and developing neural networks faster and easier.

# Why Mediapipe?
When it comes to real-time pose Estimation, _Mediapipe_ is an easier option. This is because the instances come inbuilt with the framework and can be modified. Mediapipe can build Machine Learning pipelines by processing an inputted Audio or Video.
![image](https://user-images.githubusercontent.com/70126001/190899354-8605c631-cbde-4378-affc-200b8ae5744e.png)

