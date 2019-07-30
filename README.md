# object_detection

## Problem Statement

Given an image, localize the predominant object in the image. In other words, it’s object detection without the classification part. We just had to predict the bounding boxes.

## Solution

Made use of ResNet32 model with pretrained ImageNet Weights built a Object Detection Model using fastai library. Due to lack of computational resources, I trained it for 9-10 epochs which achieved an accuracy of 65%


## Future Work

- Train it for more epochs.
- Try more models like YOLO, ResNeXt
