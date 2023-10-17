---
layout: page
title: Object Detection Project 
description: Object Detection Project in Urban Environment with SSD RESNET 50 
img: assets/img/project_object_detection/object_detection_poster.jpg #img_source: https://preimutils.readthedocs.io/en/latest/object-detection/
importance: 2
category: work
---

You can find the repository for this project [here](https://github.com/AliAfs/Object-Detection-in-an-Urban-Environment)


## 🔍 Project Overview: 
---

Object detection is a computer vision technique that allows us to identify and locate objects in an image or video. Object detection is one of the essential elements to support autonomous driving. For safe and reliable driving, autonomous vehicles rely on their perception of their surroundings. Self-driving cars obtain this perception by using object detection algorithms to make precise determinations of nearby items, such as pedestrians, automobiles, cyclists, etc.

In collaboration with the Udacity Nanodegree program, I undertook a project that sought to leverage the power of computer vision in the context of autonomous driving. The focus was on object detection, a technique vital for a vehicle's perception of its surroundings. The project involved training a convolutional neural network (CNN) to detect objects in a video feed. The CNN was trained on the Waymo dataset, which contains images of urban environments taken from real-world driving scenarios.

 The CNN was trained to detect three classes of objects: cars, pedestrians, and cyclists. The CNN was trained using the TensorFlow object detection API, which is built on top of TensorFlow 2.0.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_object_detection/training-batch.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    10 random images from training and validation sets.
</div>


## 🚗 Output:
---

Here is an illustrative example showcasing the output of object detection on test data:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_object_detection/animation.gif" title="example output" class="img-fluid rounded z-depth-1" %}
    </div>
</div>