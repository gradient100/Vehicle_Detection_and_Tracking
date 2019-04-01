# Vehicle Detection
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


In this project, a software pipeline is written to detect vehicles in a video (starting with test_video.mp4 and later implemented on full project_video.mp4), along with a detailed writeup of the project.  

The Project
---

The steps of this project are the following:

* A Histogram of Oriented Gradients (HOG) feature extraction was performed and a Linear SVM classifier was trained on a labeled training set of images
* Optionally, a color transform and binned color features could be appeneded, as well as histograms of color, to the HOG feature vector. 
*For those first two steps features were normalize and and a selection was randomized for training and testing.
* A sliding-window technique was implemented and the trained classifier was used to search for vehicles in images.
* Run your pipeline on a video stream (start with the test_video.mp4 and later implement on full project_video.mp4) and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* A bounding box for vehicles detected, was estimated.

Here are links to the labeled data for [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) and [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip) examples used to train the classifier.  These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), the [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/), and examples extracted from the project video itself.  

Some example images for testing the pipeline on single frames are located in the `test_images` folder.  Examples of the output from each stage of your pipeline in the folder called `ouput_images`, and included in the writeup for the project.  The video called `project_video.mp4` is the video your pipeline should work well on.  

The Report
---

A detailed writeup of the project is found [here](P5.pdf)

