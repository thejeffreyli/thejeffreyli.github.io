---
layout: default
---

## Projects

### All We Do Is SWIN (2023)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/pytorch-vision-transformers)

There has been a recent interest in applying Transformers to tasks in computer vision, such as image segmentation and image classification. In particular, Vision Transformers (ViT) and Hierarchical Vision Transformers via Shifted Windows were used to compare the performance of Convolutional Neural Networks (CNNs) for image classification on the CIFAR-100 dataset. Given its performance and hierarchical structure, we also explored the Swin Transformer's potential as a basis unit for encoder and decoder in generative modeling, notably Variational Autoencoder.

<img src="/assets/img/SWIN_vae_output.png" width="400">

### Classifying 3D Common Household Objects Using Deep Learning Approaches (2023)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/point-cloud-classification-exploration)

Processing 3D point cloud data is important for applications in self-driving cars, robotics, and virtual and augmented reality. Qi et al. (2017) introduced the PointNet architecture which performs classification tasks after being trained on point cloud data. The group based their design decisions on three properties of point clouds, namely permutation invariance, transformation invariance, and interactions among points. On the other hand, Zhang et al. (2023) offers a newer non-parametric approach in solving the same problem. Non-parametric building blocks are stacked across multiple stages to construct a pyramid hierarchy. We explored and evaluated both models. Firstly, we focused on implementing both networks and testing them on a smaller point cloud dataset based off ModelNet40. Secondly, we performed a series of tests on robustness on PointNet, as we augment the data during inference. Lastly, we visually assesed the internal encodings of the multistep hierarchical layers inside the non-parametric encoder of the Point-NN to understand how it captures spatial representations for classification tasks.

<img src="/assets/img/chairs.png">


### What are Those?! Sneaker Classifier (2023)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/what-are-those-sneakers)

In this project, I wanted to answer a popular question that first gained traction in 2015 from a viral Vine video: What are Those?! Often times, a sick pair of kicks in the wild catches our eye, but we have no idea what brand or model they are. I propose this program that can provide users with the correct name and model of sneakers, given an image.

The project pipeline involves six major steps: (1) gathering raw data through web-scraping images of sneakers on Google Image, (2) manually cleaning image data to ensure quality and consistency, (3) processing images and creating training and validation sets, (4) developing a convolutional neural network (CNN) architecture for multiclass classification tasks, (5) training and validating the model on sneaker images, and (6) optimizing the model through hyperparameter tuning and changes in architectural design.

<img src="/assets/img/augmentation.png" width="400">

### San Francisco Bay Area Bike Share EDA/ML Analysis (2022)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/kaggle-sf-bay-area-bike-share)

In this project, we leverage data analytics tools and machine learning algorithms to understand the San Francisco Bay Area Bike Share data provided by Kaggle. Through our exploration, we study internal and external factors that impact bike share trip durations and uncover trends across both location, time, and weather-related factors. To understand relationships between stations and key trip factors, we first use k-means clustering as an unsupervised learning method. We consider both regression and classification-based models given we have real inputs and want to predict trip durations as a continuous variable or as a categorical binary variable (i.e., short and long trips). We employ grid search cross-validation for hyperparameter tuning in order to improve our classification model and also present our final models.

<img src="/assets/img/sf_map.png" width="400">


### No Cameraman Left Behind DL/CV-based Image-Editing Software (2022)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/no-cameraman-left-behind)

In this project, we address a universal issue in taking group pictures: leaving out the photographer. Having access to a source image of only the photographer and a target image of the rest of the group, we propose a program that can incorporate both parties into one realistic final output using open-source software, namely NumPy, OpenCV, and PyTorch. The image processing pipeline involves three major steps: (1) image segmentation of person(s), (2) information extraction from the source image, and (3) gradient domain blending. 

<div style="display: flex; justify-content: space-between;">
    <img src="/assets/img/source.jpg" width="125" style="margin-right: 10px;">
    <img src="/assets/img/target.jpg" width="125" style="margin-right: 10px;">
    <img src="/assets/img/solid.jpg" width="125">
</div>
