# A Matter of Perspective: Top-Down Object Detection for Interactive Tables

![Figure1](https://user-images.githubusercontent.com/12990702/227887374-dee56891-296f-4846-9ed2-60019e0d662e.jpg)


## Abstract

While interactive tabletops have been used in a variety of applications, their high cost and fragile nature have limited their use. Projected augmented reality provides a flexible and cost-effective solution to traditional interactive tabletops. However, accurately locating and identifying objects on the table remains a challenge. To address this issue, we present a new dataset of everyday objects captured from a top-down perspective, as well as object detection models using convolutional neural networks to accurately detect objects from a top-down perspective on interactive tabletops. We demonstrate that the models can accurately locate and identify objects with a mean average precision up to 99.5\,\%. This work provides a valuable resource for the object detection community and offers a promising solution to the limitations of traditional interactive tabletops. 

## File Structure

    .
    ├── 00-Initial-Exploration            # Testing of different SOTA models
    ├── 01-Image-Capturing-Annotating     # Image capture and annotation files
    ├── 02-Image-Augmentation             # Data splitting files
    ├── 03-Model-Training                 # Model training files (EfficientDet and YOLO)
    ├── 04-Analysis                       # EfficientDet analysis files
    ├── LICENSE
    └── README.md
    
## Meeting-Logs
An overview of the project's progress, including meetings, can be viewed [here](https://github.com/vigitia/Top-Down-Object-Detection/wiki/Meeting-Logs).

## Usage
To make use of the existing files, one can easily adjust the configuration.
At the top of each notebook, there is a section with `Settings`. Here one can update the variables to point to the desired storing location.

### One note about the [image capturing process](https://github.com/vigitia/Top-Down-Object-Detection/blob/main/01-Image-Capturing-Annotating/01_capture_images_annotation.ipynb):
If you wish to add objects to the existing list, please add these at the end, since the index of the objects is used to map these to the corresponding labels in a later step.

## Contributors

&nbsp;|Name|E-Mail
-------- |--------|--------
<img src="https://avatars.githubusercontent.com/u/12990702?v=4" width="70">|Markus Bink|Markus.Bink@student.ur.de
<img src="https://avatars.githubusercontent.com/u/54026385?v=4" width="70">|Julian Höpfinger|Julian.Hoepfinger@student.ur.de

