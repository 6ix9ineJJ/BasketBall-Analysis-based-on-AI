
baskball - v5 2022-12-07 2:07pm
==============================

This dataset was exported via roboflow.com on February 17, 2023 at 6:10 AM GMT

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

The dataset includes 2583 images.
Basketball-player-hoop are annotated in YOLO v3 Darknet format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 2 versions of each source image:
* Randomly crop between 0 and 20 percent of the image
* Random rotation of between -12 and +12 degrees
* Random Gaussian blur of between 0 and 5.75 pixels


