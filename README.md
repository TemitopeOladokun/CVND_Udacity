# CVND_Udacity
Projects of Udacity Computer Vision Nanodegree 


## [Project 1: Facial Keypoints Detection](https://github.com/Tandon-A/CVND_Udacity/tree/master/Facial_Keypoints_Detection)

This project aims to build a CNN model to detect facial keypoints in an image which are the points of 'interest' in a human face such as the corners of eyes and mouth. 
 
The detection of facial keypoints allows building facial image manipulation applications. 

![Keypoint1](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/Facial_Keypoints_Detection/images/obama_points.jpg "Predicted Keypoints") 
![Keypoint2](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/Facial_Keypoints_Detection/images/obama_points2.jpg "Predicted Keypoints")

###### Fig 1: Predicted facial Keypoints


![Manipulation](https://github.com/Tandon-A/CVND_Udacity/blob/master/Facial_Keypoints_Detection/images/f3.PNG "Image Manipulation")

###### Fig 2: Sample image manipulation using facial keypoints


## [Project 2: Image Captioning](https://github.com/Tandon-A/CVND_Udacity/tree/master/Image_Captioning)

The goal of this project is to develop a deep learning model to generate captions for images. This is done using a CNN - RNN architecture following the paper [Show and Tell](https://arxiv.org/pdf/1411.4555.pdf). 

![CNN-RNN model](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/Image_Captioning/images/cnn_rnn_model.png)

###### Fig 3: [CNN RNN model](https://arxiv.org/pdf/1411.4555.pdf)

Image captioning can be used to provide verbal descriptions to partially/complete visually impaired people through a headset. It can also be used to build a query based image search engine without the need of manually annotated images. 

Some sample captions generated by the trained model are shown below. 

![Caption 1](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/Image_Captioning/images/cap1.jpg)
![Caption 2](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/Image_Captioning/images/cap2.jpg)
![Caption 3](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/Image_Captioning/images/cap3.jpg)

###### Fig 4: Generated Image Captions


## [Project 3: Landmark Detection and Tracking (SLAM)](https://github.com/Tandon-A/CVND_Udacity/tree/master/SLAM)

The goal of this project is to do landmark detection and tracking by using simultaneous localization and mapping (SLAM) for a 2D world. For this, I have implemented [graphSLAM](https://www.youtube.com/watch?v=nLEbJZFm5-E). 

![SLAM Image](https://raw.githubusercontent.com/Tandon-A/CVND_Udacity/master/SLAM/images/robot_world.png)

###### Fig 5: Final location of the robot found using SLAM

Using the robot's sensor measurements, SLAM predicts the position of the robot and the landmarks in the world. Localizing the robot in real-time builds a map of the environment.

## [Extra Curricular Project: Code Optimization](https://github.com/Tandon-A/CVND_Udacity/tree/master/optimized_code)

The goal of this project is to optimize the C++ code of the 2D histogram filter. 
Code optimizations reduce the execution time of a program while also reducing the memory footprint, making it feasible to run the code on an embedded device or in real-time scenarios. 

Execution time (in milliseconds) of the code is monitored by running every function for 10000 iterations. The best execution time achieved by the code is 16.877 milliseconds. 

| File Name  | Original Problem Code execution time | Optimized  Code execution time  | Optimized  Code execution with O3 GCC flag execution time |
 ----------- | ------------------------------------ | ------------------------------- | ----------------------------------------------------------- 
Initialize Beliefs | 43.42 | 13.518 | 1.802 |
Sense | 56.057 | 14.967 | 3.444 | 
Blur | 151.49 | 67.38 | 7.748 |
Normalize | 56.39 | 13.157 | 1.573 |
Move | 51.566 | 16.536 | 2.31 |
**Total** | **358.923** | **125.558** | **16.877** |



## Acknowledgement 

[Udacity Computer Vision Nanodegree](https://github.com/udacity/P1_Facial_Keypoints) 

## Author 
[Abhishek Tandon](https://github.com/Tandon-A)
