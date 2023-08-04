# Creating-New-Images-using-Style-Transfer-and-VGG16
Using VGG16 to extract content and style features from pictures and combining them to get a new picture

# Topic
In this notebook I will attempt to create a new picture using two images (one content image and one style image) with the help of VGG16, which is a pretrained convolutional neural network
with 16 layers that is comprised of sucessive convolution and maxpooling layers with 3 fully connected classifier layers (Although I won't be using the classifier part). The goal here is
to pass images through the convolution part of the network and extract content features i.e the general shapes from one image, and style features from the other and combine these two 
through an iterative process to create a new image. So let's get started !

# Objectives
- Extract content and style features from images
- Create new pictures by combining the content and style of different images

# Summary
- Importing Libraries
- Loading the model
- Attempt 1: planets and cherry blossom
- Attempt 2: portrait and painting
- Attempt 3: statues and colors
- Conclusion
- References


# Libraries:
- Numpy
- Torchvision
- Pil
- Torch

# Paper Reference

https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf
