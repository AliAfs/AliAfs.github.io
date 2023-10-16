---
layout: page
title: Object Detection Project 🚗
description: Object Detection Project in Urban Environment with SSD RESNET 50 
img: assets/img/project_object_detection/object_detection_poster.jpg #img_source: https://preimutils.readthedocs.io/en/latest/object-detection/
importance: 2
category: work
giscus_comments: true
---

## 🔍 Project Overview: 
---

Object detection is a computer vision technique that allows us to identify and locate objects in an image or video. Object detection is one of the essential elements to support autonomous driving. For safe and reliable driving, autonomous vehicles rely on their perception of their surroundings. Self-driving cars obtain this perception by using object detection algorithms to make precise determinations of nearby items, such as pedestrians, automobiles, cyclists, etc.

In collaboration with the Udacity Nanodegree program, I undertook a project that sought to leverage the power of computer vision in the context of autonomous driving. The focus was on object detection, a technique vital for a vehicle's perception of its surroundings. The project involved training a convolutional neural network (CNN) to detect objects in a video feed. The CNN was trained on the Waymo dataset, which contains images of urban environments taken from real-world driving scenarios.

 The CNN was trained to detect three classes of objects: cars, pedestrians, and cyclists. The CNN was trained using the TensorFlow object detection API, which is built on top of TensorFlow 2.0. The CNN was trained on a GPU-enabled Google Cloud Platform (GCP) instance. The trained model was then deployed to a Jetson Nano, a small, low-power computer that can be used for edge computing. The Jetson Nano was connected to a webcam, and the trained model was used to detect objects in the webcam's video feed. The project was a success, and the CNN was able to detect objects in the video feed with a high degree of accuracy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_object_detection/training-batch.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    10 random images from training and validation sets.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
