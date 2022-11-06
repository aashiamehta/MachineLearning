# CS 7641: Machine Learning
#### Project 3: Unsupervised Learning
#### By: Aashia Mehta

### How to Run Code

GitHub URL: https://github.com/aashiamehta/MachineLearning/tree/main/Project3

In order to run the main code, please refer to: ```unsupervised_learning.ipynb```.

The dataset in the directory is:```wine_quality.csv``` and ```phishing_websites.csv```.

1. Install miniconda (https://docs.conda.io/en/latest/miniconda.html).
2. Run the following commands to create an environment and install dependencies:
- ```conda create --name ml_env python=3.7 -y```
- ```conda activate ml_env```
- ```pip install -r requirements.txt```
3. Run this command to start up jupyter notebook:
- ```jupyter notebook```
4. Go to a browser and type in localhost:8888


### Description

In this project, I explored two clustering algorithms (k-means, Expectation Maximization) and four dimensionality reduction algorithms (PCA, ICA, Randomized Projections, and LDA).

The datasets I used can be found here:
- https://archive.ics.uci.edu/ml/datasets/phishing+websites
- https://archive.ics.uci.edu/ml/datasets/wine+quality