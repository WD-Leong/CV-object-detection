# Fully Convolutional One-Stage Object Detection (FCOS)
This repository contains my implementation of the [FCOS](Fully Convolutional One-Stage Object Detection) object detection architecture. This is still work-in-progress.

## Losses
The original paper uses Binary Cross Entropy (BCE) for as the loss function for centerness and Intersection over Union (IoU) Loss for the bounding boxes. In the code, the Smooth L1-loss is implemented instead of IoU loss and BCE as it appeared to stabilize the training. However, it does support IoU loss (uncomment the relevant lines in the code). 