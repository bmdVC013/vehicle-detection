# Linear SVM pipline: Vehicle Detection
*In this project, goal is to write a software pipeline to detect vehicles in a image or a video.*

It can be achieved by following the below tasks:
+  Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier.
+ Implement a sliding-window technique and use your trained classifier to search for vehicles in images.
+ Run pipeline on a video stream and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
+ Estimate a bounding box for vehicles detected.

## Datasets
Here are links to the labeled data for [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) and [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip) examples to train your classifier. These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), [KITTI vision benchmark suite](http://www.gti.ssr.upm.es/data/Vehicle_database.html), and examples extracted from the project video itself. You are welcome and encouraged to take advantage of the recently released [Udacity labeled dataset](https://github.com/udacity/self-driving-car/tree/master/annotations) to augment your training data.

## Performance
The accuracy on the test set is above 97% with 8792 vehicle images and 8968 non-vihicle images.

## Examples
![vehicle](images/figures/vehicl_detect_on_image.png)

<img src="https://media.giphy.com/media/i3CLrpVj0GlIV9aHQJ/giphy.gif" width="500" height="350"/>

## Preferences
[Vehicle Detection](https://github.com/udacity/CarND-Vehicle-Detection) - Udacity
