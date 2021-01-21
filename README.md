# Computer-Vision

## Object Tracking with OpenCV and Python

**Project Overview**

* Task 1: Introduction
* Task 2: Optical Flow (in 4 parts)
* Task 3: Dense Optical Flow (in 2 parts)
* Task 4: MeanShift (in 3 parts)
* Task 5: CamShift
* Task 6: Single Object Tracking (in 3 parts)
* Task 7: Multi Object Tracking (in 3 parts)

### How to Tune Cascade Classifier

https://docs.opencv.org/2.4/modules/objdetect/doc/cascade_classification.html#cascadeclassifier-detectmultiscale

**detectMultiscale**(input image, **Scale Factor**, **Min Neighbors**)

* **Scale Factor** Parameter specifying how much yhe image size is reduced at each image scale.
* **Min Neighbors** Parameter specifying how many neighbors each candidate rectangle should have to retain it.

### HSV colorspace
https://docs.opencv.org/3.4/da/d97/tutorial_threshold_inRange.html