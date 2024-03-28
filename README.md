# Football Object Detection with YOLOv8

This repository hosts a pretrained YOLOv8 model designed for object detection in football matches. The model is trained on a custom dataset annotated using Roboflow, enabling it to detect four key classes: football players, ball, referee, and goalkeeper. Testing has been conducted on both images and videos, and the results are provided in the repository.

## Dataset

The dataset utilized for training comprises manually annotated images extracted from various football matches. These annotations provide the necessary labels for the model to recognize the specified classes accurately. The dataset is accessible in the `/dataset` directory.

## Results

The outcomes of the object detection process are available for review:

- **Images:** Results of object detection in images can be found in the `/results` directory.
- **Videos:** The model's performance has been evaluated on videos, and sample results are included in the `/results` section.
