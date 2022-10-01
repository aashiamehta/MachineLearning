# CS 7641: Machine Learning
#### Project 2: Randomized Optimization
#### By: Aashia Mehta

### How to Run Code

GitHub URL: https://github.com/aashiamehta/MachineLearning/tree/main/Project2

In order to run the main code, please refer to: ```randomized_optimization.ipynb```.

The dataset in the directory is:```wine_quality.csv```.

1. Install miniconda (https://docs.conda.io/en/latest/miniconda.html).
2. Run the following commands to create an environment and install dependencies:
- ```conda create --name ml_env python=3.7 -y```
- ```conda activate ml_env```
- ```pip install -r requirements.txt```
3. Run this command to start up jupyter notebook:
- ```jupyter notebook```
4. Go to a browser and type in localhost:8888


### Description

In this project, I explored four local random search algorithms: 
- randomized hill climbing
- simulated annealing
- a genetic algorithm
- MIMIC

The dataset I used can be found here:
- https://archive.ics.uci.edu/ml/datasets/wine+quality