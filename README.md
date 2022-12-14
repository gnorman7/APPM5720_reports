# README

This repository is a collection of the seven biweekly reports that I created for APPM 5720: Special Topics: Applied Deep Learning, in Fall 2022, taught by Professor Maziar Raissi.
The course material is publicly available [here](https://github.com/maziarraissi/Applied-Deep-Learning).
These reports (along with peer grading other students' reports) formed 100% of my grade in the course.
The topics are briefly described below:

Report 1. I explore PyTorch's automatic differentiation, investigating back propagation and optimizers for a problem of least-squares linear regression.
Report 2. I implement a Convolutional Neural Network for the MNIST digits dataset and discuss dimensionality reduction methods to visualize the loss landscape. I also provide a quick comparison of GPU vs. CPU runtimes for matrix-vector multiplication.
Report 3. I go through a least-squares problem again, this time focusing on the importance of normalizing inputs and touching upon feature engineering. I also discuss classical $L^2$ regularization and Extreme Learning Machines.
Report 4. I load the pretrained SqueezeNet model from PyTorch and demonstrate how image classification models in PyTorch may be used. Then, I create a simple adversarial attack to fool the image classifier.
Report 5. I explore the basics of the hyperparameter tuning library, [Ray Tune] (https://docs.ray.io/en/latest/tune/index.html), focusing on Bayesian Optimization.
Report 6. For the Labeled Faces in the Wild dataset, I explore compression and generation methods through the Singular Value Decomposition.
Report 7. Using the Keypoint RCNN model, I briefly investigate the area of pose estimation, specifically for photos of climbers.

**None of the images or loaded data in any of these reports are mine. The liscense does not necessarily apply to these images or data and the original source should be referenced instead.**

I have made these reports publically viewable for other students interested in the class, for people starting the field of Machine Learning to reference, and as a set of examples of my own interests.


The reports are included as their own repositories and added to this repository through git's submodules. To download all the repositories, add the option `--recurse-submodules` (or `--recursive`) to the `git clone` command.


