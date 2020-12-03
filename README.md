# CS499 - Deep Learning (Fall 2020)
## Final Team Project
### Project: Object Detection for Food Waste Reduction
### Team member: Junhyeok Jeong, Zhuohong Gu, Ashyan Ashley Rahavi



## Before run the project
### make sure to install opencv +4.x
### Since original YOLOv3 weight file is too heavy, please download here:
### https://pjreddie.com/media/files/yolov3.weights
### and put the file in trained_data/original_yolov3

## How to run the project
### 1. Detect object of the input image file
### python3 yolo_img.py [image file path] -w [choose one: tiny, shape, original]
### 2. Detect object with webcam (real time)
### python3 yolo_webcam.py -w [choose one: tiny, shape, original]
