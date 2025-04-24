SVHN
Google Street View House Number(SVHN) Dataset [Link](http://ufldl.stanford.edu/housenumbers/)

Much similar to MNIST(images of cropped digits), but SVHN contains much more labeled data (over 600,000 images) with real world problems of recognizing digits and numbers in natural scene images.

Overview:
Total 10 Classes, 1 for each digits i.e Label '9' for digit 9 and '10' for digit 0.
73,257 digits for training, 26,032 digits for testing

Available in two differnet formats
Original images with bounding box available for each character (may contain multiple characters in same images).
MNIST like 32x32 cropped images having single character in each images.
Dataset is obtained from house numbers in Google Street View images.

Here we are classifying 32 x 32 cropped images given in format 2
Using CNN architecture.

Train_32x32
Test_32x32
