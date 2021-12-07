CONTENTS OF THIS FILE

* Introduction
* Requirements
* Installation
* Directory Structure
* Usage
* Credits

# Introduction

This assignment is intended to classify river and non river regions of images taken from satellite using k-means clustering. The output image consists of classified images based on value of k = 2,3,4, and 5. Also, Silhouette coefficient comparison plot was done for k =2,3,4,5.

Dataset Information:

Link: https://www.isical.ac.in/~murthy/
Description: Images of calcutta in four different bands (.gif)

# Requirements

1. Python 3
2. Numpy
3. Matplotlib
4. PIL (Python Imaging Library)
5. Jupyter Notebook

# Installation

1. Python

Step 1: Visit and download Python from https://www.python.org/downloads/
Step 2: Install and add Python to path

2. Numpy

In command prompt
> pip install numpy

3. Matplotlib

In command prompt
> pip install matplotlib

4. PIL

Direct Link: https://pypi.python.org/packages/3.4/P/Pillow/Pillow-2.5.3.win-amd64-py3.4.exe#md5=6ee659d7b945e826a07c53c15578424f

5. Jupyter

In command prompt
>pip install jupyterlab

For conda users
>conda install -c conda-forge jupyterlab

To start Jupyter type 
>jupyter notebook

# Directory Structure

Project Folder
|---- src
|       |---- band1.gif
|       |---- band2.gif
|       |---- band3.gif
|       |---- band4.gif
|       |---- k_means.ipynb
|
|---- output
|       | ---- output_1_k_2.png
|       |---- output_2_k_3.png
|       | ---- output_3_k_4.png
|       | ---- output_4_k_5.png
|       | ---- output_5_s_curve.png
|---- documentation.pdf
|---- readme.txt


# Usage

The src folder contains a jupyter notebook, and four .gif images. The output folders contains the output images of the classified satellite image. Also, it contains the silhouette curve. The documentation.pdf contains the printed version of the notebook.

# Credits

Author: Ajay Biswas
Email: 220cs2184@nitrkl.ac.in
Rollno.: 220CS2184
M.Tech. Information Security, NIT Rourkela, India.

ML Lab M.Tech (CS6272)
Assignment 10 : k-Means Clustering on Satellite Images. 

