# Motion-Detection



📌 Project Overview

This project is a computer vision application that detects motion and tracks moving objects (primarily people) in video streams using OpenCV. It compares consecutive frames to identify moving regions and highlights them with bounding boxes.
✨ Key Features

    Real-time motion detection in video streams

    Background subtraction using frame differencing

    Noise reduction with Gaussian blur

    Adaptive thresholding for movement detection

    Contour analysis to identify significant moving objects

    Customizable parameters for different environments

    Visual tracking with bounding boxes

🛠️ Technical Implementation
Core Technologies

    Python 3.x

    OpenCV (cv2) library

    Computer vision techniques:

        Frame differencing

        Image thresholding

        Contour detection

        Morphological operations

Main Components

    Video Capture: Reads input from video files or cameras

    Frame Processing:

        Resizing for performance

        Grayscale conversion

        Gaussian blur for noise reduction

    Motion Detection:

        Absolute difference between frames

        Thresholding to identify moving pixels

        Dilation to enhance moving regions

    Object Tracking:

        Contour detection

        Area-based filtering

        Bounding box drawing
