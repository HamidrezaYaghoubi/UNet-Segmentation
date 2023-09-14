# UNet Segmentation
Welcome to my U-Net image segmentation project! In this repository, I'll guide you through building your own U-Net, a powerful convolutional neural network designed for precise image segmentation. We'll use this network to predict labels for every pixel in images from the CARLA self-driving car dataset.

## What is Semantic Image Segmentation?
Semantic image segmentation is a fascinating task in computer vision. It goes beyond traditional object detection by not only identifying objects in an image but also precisely outlining them at the pixel level. Think of it as creating an intricate map for each object, where every pixel is labeled with its corresponding class. For example, in an image of a street scene, "Car" pixels might be marked in dark blue, and "Person" pixels could be highlighted in red:

![download](https://github.com/hamidrezayaghobi/Deep-Learning-Grad-HW02-UNet-Segmentation/assets/59170724/4e48f2f8-782d-4152-82ef-4dcada0a2221) </br>
<u><b>Figure 1</u></b>: Example of a model's output<be>

This level of detail is essential for applications like self-driving cars, which require a granular understanding of their surroundings to make safe decisions. With semantic segmentation, I can identify lanes, other vehicles, pedestrians, and more with pixel-perfect accuracy.

## What You'll Learn
By the end of this project, you'll achieve the following milestones:

1- **Build Your Own U-Net:** You'll have hands-on experience in constructing a U-Net architecture, gaining insights into its key features and benefits.

2- **Understanding U-Net:** You'll grasp the fundamental differences between a regular convolutional neural network (CNN) and the U-Net architecture.

3- **CARLA Dataset:** I'll work with the CARLA self-driving car dataset, applying semantic image segmentation to real-world images.

4- **Pixelwise Prediction:** You'll implement the sparse categorical cross-entropy loss function for pixel-wise prediction, a crucial step in semantic segmentation.
