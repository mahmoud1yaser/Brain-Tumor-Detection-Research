# Deep-Tumor-Insight

## Table of Contents
- [Project](#project)
- [Information](#information)
- [Technologies](#technologies)
- [Setup](#setup)
- [Poster](#poster)
- [Notebook](#notebook)
- [Report](#report)
- [Presentation](#presentation)
- [Team](#team)

<hr>

## Project

1. Data Exploration
- The Brain Tumor Detection 2020 Kaggle dataset, consisting of 3065 MRI images separated into two classes (Tumor – Non-Tumor) brain, was used.

2. Data Analysis
- cv2.COLOR_RGB2LAB was used to apply equalization histogram to perceptual lightness.
- Analysis of histograms indicated that the affected brains had much more perceptual lightness intensity.

3. CNN Model
- The model included mainly 3 Conv2D layers with maxpooling and ReLU activation functions, followed by Flatten, Dense, Activation, Dropout, Dense and Activation layers.

4. Model Training
 - Binary crossentropy loss function was used for binary classification.
- Adam optimizer, a stochastic gradient descent optimization algorithm, was chosen to train the deep learning model as it can handle sparse gradients on noisy problems.

5. Model Evaluation
- The model achieved a validation accuracy of 97% which indicates its potential for detecting brain tumors accurately.
 

## Information
- This project is Mathematical Modeling using PDEs for Detection of Brain Tumor which was required by our college to further join a competition where our team pirates got the 2nd place in it. The content of this project includes:
    - Poster which illustrates our full project
    - Implementing our algorithm using Deep Learning to detect brain tumor in Jupyter Notebook (Accuracy 97%)
    - Report which describes the full research process
    - Presentation to present our full idea

<hr>

## Technologies
- NumPy
- Matplotlib
- Keras
- TensorFlow
- PIL
- SciPy

<hr>

## Setup

To run this project, install it locally using pip:

Shell

    $ cd ../"project_path"
    $ jupyter notebook brain-tumor-detection-notebook.ipynb

<hr>

## Poster

[Project Poster](assets/DeepTumorInsight_poster.pdf)
<hr>

## Notebook

[Project Notebook](DeepTumorInsight_notebook.ipynb)
<hr>

## Report

[Project Report](assets/DeepTumorInsight_report.pdf)

<hr>

## Presentation

[Project Slides](assets/DeepTumorInsight_slides.pptx)

<hr>

## Team
Name|
--- |
Mahmoud Salman|
Ibrahim Mohamed|
Kamel Mohamed|
Youssef Shaaban|
Dina Khalid|
Youssef Kadry|
Neveen Mohamed|
Esraa Ali|

<hr>
