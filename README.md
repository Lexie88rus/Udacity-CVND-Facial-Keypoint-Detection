# Udacity-CVND-Facial-Keypoint-Detection
Repository containing the materials for Udacity CVND Facial Keypoint Detection project

## About the Project
Facial keypoints include points around the eyes, nose, and mouth on a face and are used in many applications.
These applications include: facial tracking, facial pose recognition, facial filters, and emotion recognition.
The implemented solution is able to look at any image, detect faces, and predict the locations of facial keypoints on each face. Some examples of these keypoints are pictured below.

## Implementation
The complete computer vision pipeline consists of:
1. Detecting faces on the image with [OpenCV](https://opencv.org) [Haar Cascades](https://en.wikipedia.org/wiki/Haar-like_feature).
2. Detecting 68 facial keypoints with CNN with architecture based on [this paper](https://arxiv.org/pdf/1710.00977.pdf).

## Examples
![image](https://github.com/Lexie88rus/Udacity-CVND-Facial-Keypoint-Detection/raw/master/assets/demo_image.jpg)
