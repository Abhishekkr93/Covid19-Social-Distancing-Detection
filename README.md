# Covid19-Social-Distancing-Detection
 This is a Social Distancing Detector project.

# Social Distancing Detector and Monitoring Project, COVID-19 Tracker
This project uses Deep Learning based YOLOv3 Pretrained model for object Detection, OpenCV python library for image processing and Centroid Tracking Algorithm For object  tracking. In this project, I am attaching the code for building a Social Distancing Detector to detect if a crowd is practicing Social Distancing or not, using a sample video.

Social Distancing is one such terminology that has gained popularity over the past few months, thanks to COVID-19. People are forced to maintain a sufficient amount of distance between each other to prevent the spread of this deadly virus. Amidst this crisis, I and My Project Team decided to build a simple Social Distancing Detector that could monitor the practice of social distancing in a crowd.

## Programming languange & Algorithm used:
- [Python](https://www.python.org/)
- [YOLOv3 model](https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/)

## Technology Used:
- [OpenCV](https://opencv.org/) (for frame/image processing)
- [Deep Learning](https://machinelearningmastery.com/what-is-deep-learning/) (Used YOLOv3 Pretrained model for object Detection-(used filter for people indentification only))
- [Centroid Tracking Algo](https://en.wikipedia.org/wiki/Track_algorithm) (For object  tracking)

## Dependencies:
- imutils==0.5.3
- numpy==1.18.5
- opencv-python==4.2.0.34
- pkg-resources==0.0.0
- scipy==1.4.1

## How to run?
### [Google Colab Notebook](https://colab.research.google.com/drive/1R4maYW9mIB1WcKtrvqNdVybC4OacyAMI?usp=sharing)

- PLEASE DOWNLOAD THE YOLOv3 MODEL FROM BELOW LINK AND KEEP ALL THE DOWNLOADED FILES INSIDE THE SAME FOLDER
   - [Download YOLOv3 Model](https://drive.google.com/drive/folders/1s5yXMDwjcUsfX5VxuFFAZrPIjkbiQ7h6)
  
- clone the repository to your local machine
- navigate to this cloned directory
- from the terminal install dependencies using these commands:
  - python -m pip install opencv-python
  - from scipy.spatial import distance as dist
  - import numpy as np
  - import argparse
  - import imutils
  - import os
- after installing the dependencies run the <span>social_distancing_config.cpython</span> file from terminal using this command:
  - python <span>social_distancing_config.cpython</span>
- To analyze the different sample videos & Execute, Follow this:-
  - example: <br/>
    `python social_distance_detector.py --input VIDEO1.mp4 --output OUTPUT1.mp4` for first Video <br/>
    `python social_distance_detector.py --input VIDEO2.mp4 --output OUTPUT2.mp4` for second Video <br/>
    and so on.

## RESULTS OF MODEL VIDEO ON TESTING:

# 1. 

### Video1 Input:-

![VIDEO3](https://user-images.githubusercontent.com/56020385/118154372-97063e80-b434-11eb-82dc-6b6418ea503b.gif)

### Video1 Output:-

![output one](https://user-images.githubusercontent.com/56020385/118194770-8f13c200-b467-11eb-8948-f65c5946fdce.gif)

# 2. 

### Video2 Input:-

![two output gif](https://user-images.githubusercontent.com/56020385/118197367-6a6e1900-b46c-11eb-917c-203be17b8d9e.gif)

### Video2 Output:-

![ezgif com-video-to-gif(1)](https://user-images.githubusercontent.com/56020385/118197688-0bf56a80-b46d-11eb-8ab1-33b052266767.gif)


### This is Computer Vision And Image Processing project which can be used for monitoring social distancing in Lockdown & to fight against COVID-19 a.k.a. the Corona Virus.
## Fell free to contribute to this project by providing more sample videos, your contribution will be appreciated.

<br/>

# Thank You!
