# YOLOv5x Object Detection for Cluttered Indoor Shots

This was done as a part of my Computer Vision Final Project 2021.
This implements:
* Model evaluations on pretrained YOLOv5x on different datasets.
* Custom Trained YOLOv5x on VPLab Dataset to improve results on cluttered indoor settings.
* Real-time running Gradio app as a prototype demo.


### More details on the projects are detailed in the [Report](./Report.pdf) above.
Some important information and images are shown below.


### Dependencies:
* Google Collab
* Pytorch (torch and torchvision)
* Ultralytics
* OpenCV  
* FiftyOne
* PIL
* Numpy
* Matplotlib
* Path
* Gradio

## Real-time Gradio app
<img src='https://user-images.githubusercontent.com/64144419/144751675-85126ce2-5b37-4dd1-b67e-554f39afd911.png' width=800>

## Comparison of Pretrained and Custom Trained
<figure>
  <img src='https://user-images.githubusercontent.com/64144419/144751806-8e7f8c10-121a-4364-bb9a-e3dda4b13849.png' width=800 caption='sdasd'>
  <figcaption>First row: Input, Second
row: Ground truth, Third row: Pretrained Yolo v5x, Fourth row: Custom-trained Yolo v5x</figcaption>
</figure>

## Comparison of MAP, Precision, Recall Scores for Pre-trained and Custom-trained Yolo v5x
<img src='https://user-images.githubusercontent.com/64144419/144751961-754a305f-545f-40e7-aed2-8d11868d11a7.png' width=800>

## Bar graphs showing the improvement of Precision, Recall scores over different classes, and overall MAP improvement
![image](https://user-images.githubusercontent.com/64144419/144752012-374f8e92-0d57-467c-a4bc-f4ef4bcac0f5.png)
![image](https://user-images.githubusercontent.com/64144419/144752017-e0018397-ea6a-416f-b697-cea4588723b8.png)


