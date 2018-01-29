# Object Recognition with OpenCV on Android

We will look at how to use the OpenCV library to recognize objects on Android using feature extraction.

# Requirements

# 1. Android Studio
# 2. Opencv-3.4.0-android-sdk
# 3. Latest android build tools


# Getting started


I am using Android Studio and you can follow the link(https://developer.android.com/studio/index.html) to download and install Android studio and SDK tools 


You have to download and import OpenCV library to android studio and there is a stackoverflow answer which you can follow to setup everything.link(https://stackoverflow.com/questions/27406303/opencv-in-android-studio)
 The algorithm we are going to use is ORB(Oriented FAST and Rotated BRIEF).
Here is a link-->  (https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_feature2d/py_table_of_contents_feature2d/py_table_of_contents_feature2d.html) for the other existing algorithms in OpenCV for object detection


 I am giving this link(https://developer.android.com/studio/projects/create-project.html) so you could follow that and create a new project.
 
 It is important to have the input image and the image that you receive from the camera has the same dimensions. before I insert the image to the assets folder in the project. if there is a mismatch between your image’s dimensions, image’s type you will get few errors. I got them and I solved them using the following two links.
 (https://stackoverflow.com/questions/27813446/opencv-error-assertion-failed-src-dims-2-info-height-uint32-t)
 (https://stackoverflow.com/questions/6910332/convert-matrix-of-type-cv-32fc1-to-cv-64fc1)
 Then you can create an assets folder on android and then you can copy paste the image to that folder. You can follow this link(https://stackoverflow.com/questions/18302603/where-do-i-place-the-assets-folder-in-android-studio) to create an assets folder inside your project.
 
Thanks!!!!!!!!


 
 
