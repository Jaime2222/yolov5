
Football_analytics_final - v11 final_augmentation_v1.1
==============================

This dataset was exported via roboflow.ai on December 11, 2021 at 3:35 PM GMT

It includes 1564 images.
Visionarios are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -2 and +2 degrees
* Random brigthness adjustment of between -30 and +30 percent


