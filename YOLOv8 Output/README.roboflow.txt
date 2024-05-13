
logo-dataset - v6 Text + shape
==============================

This dataset was exported via roboflow.com on January 20, 2024 at 12:44 PM GMT

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

The dataset includes 14828 images.
Brand-logos are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)
* Auto-contrast via histogram equalization

The following augmentation was applied to create 2 versions of each source image:

The following transformations were applied to the bounding boxes of each image:
* Random rotation of between -15 and +15 degrees
* Random shear of between -4° to +4° horizontally and -4° to +4° vertically
* Random brigthness adjustment of between 0 and +23 percent


