# Welcome!

## Biography	
I am a second year graduate student in the [Scientific Computing Master's Program (SCMP)](https://pics.upenn.edu/masters-science-engineering-scientific-computing/) at the University of Pennsylvania. I obtained my Bachelor's at Emory University, where I studied Chemistry and Computer Science. My work and research experiences range from studying potential energy surfaces to developing analytics tools for businesses. My current interests are in applied machine learning, computer vision, and deep learning. Outside of work, I enjoy running, playing/watching soccer and basketball, and collecting sneakers.

<!-- ![Bike Study](/assets/img/peachtree2023.JPG) -->

## Education							       		

- **University of Pennsylvania**, Master of Science in Engineering, Scientific Computing (_May 2024_)	
- **Emory University**, Bachelor of Science in Chemistry, Bachelor of Arts in Computer Science (_May 2021_)


## Experience
**Data Science Intern @ Federal Reserve Bank of Atlanta (_May 2023 - August 2023_)**
- Developed robust and efficient web scraping solutions using Python, LXML, and Selenium that automated data retrieval tasks on public domains, reduced manual efforts, and achieved up to an 88% improvement in speed.
- Employed NLP techniques, specifically TF-IDF, to analyze over 3,000 employee reviews and identify insights and trends, providing stakeholders with valuable information on employee sentiments. 
- Performed comprehensive data preprocessing using Pandas to clean and prepare raw data from financial institutions, and subsequently produced interactive dashboards and visualizations in Tableau to showcase findings to examiners. 
- Converted and refined existing SAS source code to Python and SQL for generating viable datasets to train risk assessment models.


**Head Graduate Teaching Assistant for CIS 5450 ([Big Data Analytics](https://sites.google.com/seas.upenn.edu/cis545/home?authuser=1)) @ University of Pennsylvania (_January 2023 - Present_)**
- Oversee a team of TAs in the ongoing, collaborative development of course content and structure for 400 students.
- Host recitations, review sessions, and weekly office hours to aid students with assignments and lecture concepts.
- Mentor six groups of three students on end-of-term projects by providing guidance and constructive feedback.
- Curate and grade course material, including exams and homework assignments. 

**Machine Learning Research Intern @ Argonne National Laboratory (_June 2021 - August 2021_)**
- Familiarized myself with computer vision techniques and convolutional neural network (CNN) architecture through reading documents, literature, and online resources and through asking questions.
- Produced a comprehensive pipeline using NumPy and OpenCV for time-lapsed image labeling and preprocessing that prepared input data for downstream segmentation tasks and significantly reduced manual efforts. 
- Actively collaborated in the training process of U-Net model in PyTorch for image segmentation of snow rods.

**Computational Chemistry Research Assistant @ Joel Bowman Research Group, Emory University (_August 2020 - August 2022_)**
- Designed, implemented, and tested a desktop GUI using Python and PyQt for running monomial symmetrization fitting software, ensuring a seamless user experience. 
- Explored alternate methods for identifying negative potentials in potential energy surface fits through assessing diffusion Monte Carlo calculations and artificially reduced masses.
- Cleaned and processed data using Scikit-learn and Pandas to assess coverage and identify patterns.
- Assisted Dr. Bowman in his Machine Learning in Chemistry capstone course. Introduced students to a relatively new topic through teaching the first lecture.

## Highlighted Projects

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

<br>

#### [Check out more projects here!](./projects.html)


## Publications
1. Houston, P. L., Qu, C., Yu, Q., Conte, R., Nandi, A., Li, J., Bowman, J. M. (2023). PESPIP: A Software to Fit Complex Molecular and Many-body Potential Energy Surfaces with Permutationally Invariant Polynomials. 158 (4). Journal of Chemical Physics. [Read](https://doi.org/10.1021/acs.jctc.0c00001). 
2. Chu, M., Li, J., Zhang, Q., Jiang, Z., Dufresne, E. M., Sandy, A., Narayanan, S., Schwarz, N. (2022). pyXPCSviewer: an open-source interactive tool for X-ray photon correlation spectroscopy visualization and analysis. Journal of Synchrotron Radiation. 29, 1122-1129. [Read](https://doi.org/10.1107/S1600577522004830). 
3. Li, J., Qu, C., Bowman, J. M. (2021). Diffusion Monte Carlo with Fictitious Masses Finds Holes in Potential Energy Surfaces. Molecular Physics. 119(17-18). [Read](https://doi.org/10.1080/00268976.2021.1976426). 
4. Conte, R., Houston, P. L., Qu, C., Li, J., Bowman, J. M. (2020). Full-dimensional, ab initio potential energy surface for glycine with characterization of stationary points and zero-point energy calculations by means of diffusion Monte Carlo and semiclassical dynamics. The Journal of Chemical Physics. 153(244301). [Read](https://doi.org/10.1063/5.0037175). 
