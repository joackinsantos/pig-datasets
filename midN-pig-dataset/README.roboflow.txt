
pig-dataset - v2 2023-05-17 7:17pm
==============================

This dataset was exported via roboflow.com on May 17, 2023 at 12:48 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 6675 images.
Pig-heads-and-rears are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise
* Randomly crop between 0 and 50 percent of the image
* Random rotation of between -35 and +35 degrees
* Random brigthness adjustment of between -20 and +20 percent


