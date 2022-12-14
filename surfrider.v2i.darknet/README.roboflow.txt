
surfrider - v2 2022-12-05 9:25pm
==============================

This dataset was exported via roboflow.com on December 5, 2022 at 8:27 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 1200 images.
Detection-of-plastics-in-rivers are annotated in YOLO v3 Darknet format.

The following pre-processing was applied to each image:
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Random Gaussian blur of between 0 and 2.25 pixels
* Salt and pepper noise was applied to 1 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip
* 50% probability of vertical flip


