
BCCD - v4 416x416_aug
==============================

This dataset was exported via roboflow.com on July 14, 2022 at 9:28 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 874 images.
Cells are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 15 percent of the image
* Random brigthness adjustment of between -15 and +15 percent
* Random exposure adjustment of between -20 and +20 percent


