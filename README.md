# SLIC-and-Image--Segmentation

### In this assignment we are asked to perform 3 tasks:
#### 
1. Generate superpixel maps using K means clustering.
2. Generate Superpixel maps using SLIC algorithm.
3. Build a segmentation and classification network by training a deep neural network on the superpixels. To achieve this the following steps has to be taken:

    a. Dilate and save each superpixel region from SLIC output into image of size 224X224, alongwith the ground truth segments label.
    b. Build a couple of convolution layers to extract the deep features from each Superpixel patch image. Let the last layer be Fully connected layers.
    c. Define the segmentation loss as multi-class classification loss and train a convolutional neural network based classifier.

Then, during inference, we have to combine the classifier's predicted labels to form the whole input image's Superpixel segmentation results.
