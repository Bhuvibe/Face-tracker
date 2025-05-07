Face Tracker Using OpenCV

This project demonstrates a real-time face tracking system developed using Python and OpenCV. It is designed to detect human faces from a video stream (such as a webcam feed) and track their movement across successive frames. The system combines face detection techniques with tracking algorithms to achieve smooth and consistent tracking performance.

Initially, the face detection component identifies faces in the video frame using a pre-trained Haar cascade classifier (or other classifiers such as DNN-based models, if used). Once a face is detected, a tracking algorithm—such as KCF (Kernelized Correlation Filters), CSRT (Discriminative Correlation Filter with Channel and Spatial Reliability), or others—is initialized to follow the face as it moves within the video feed.

This project is useful for applications such as surveillance, user interaction systems, and motion analysis. It provides a foundation for more complex systems involving face recognition, behavior analysis, or multi-object tracking.

Key Features:

Real-time face detection and tracking

Uses OpenCV’s built-in tracking algorithms

Option to switch between different trackers (e.g., KCF, CSRT, MIL)

Simple and efficient implementation using Python
