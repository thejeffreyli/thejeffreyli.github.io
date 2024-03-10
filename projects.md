---
layout: default
---

## Highlighted Projects

### San Francisco Bay Area Bike Share EDA/ML Analysis (2022)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/kaggle-sf-bay-area-bike-share)

In this project, we leverage data analytics tools and machine learning algorithms to understand the San Francisco Bay Area Bike Share data provided by Kaggle. Through our exploration, we study internal and external factors that impact bike share trip durations and uncover trends across both location, time, and weather-related factors. To understand relationships between stations and key trip factors, we first use k-means clustering as an unsupervised learning method. We consider both regression and classification-based models given we have real inputs and want to predict trip durations as a continuous variable or as a categorical binary variable (i.e., short and long trips). We employ grid search cross-validation for hyperparameter tuning in order to improve our classification model and also present our final models.

<img src="/assets/img/sf_map.png" width="400">


### No Cameraman Left Behind DL/CV-based Image-Editing Software (2022)

[Check out the full GitHub Repo!](https://github.com/thejeffreyli/no-cameraman-left-behind)

In this project, we address a universal issue in taking group pictures: leaving out the photographer. Having access to a source image of only the photographer and a target image of the rest of the group, we propose a program that can incorporate both parties into one realistic final output using open-source software, namely NumPy, OpenCV, and PyTorch. The image processing pipeline involves three major steps: (1) image segmentation of person(s), (2) information extraction from the source image, and (3) gradient domain blending. From qualitative tests, our program works well on images with people standing in front of a solid background and with people standing next to each other on the horizontal axis. The final product rivals the results manually produced using Adobe Photoshop software. The program performs suboptimally on images with complex backgrounds, with people standing at different locations in the foreground, and images taken at different angles. Future work can be done to improve the robustness of our program and to combat more edge cases. 

<div style="display: flex; justify-content: space-between;">
    <img src="/assets/img/source.jpg" width="125" style="margin-right: 10px;">
    <img src="/assets/img/target.jpg" width="125" style="margin-right: 10px;">
    <img src="/assets/img/solid.jpg" width="125">
</div>
