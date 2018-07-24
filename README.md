# Census Income Dataset Classification
Data Science Notebook on a Classification Task

## Objective
In the Jupyter Notebook included in this page, we will using the Census Income Dataset to predict whether an individual's income exceeds $50K/yr based on census data.

The Dataset can be found here:
- https://archive.ics.uci.edu/ml/datasets/adult

The Notebook can be found here:
- https://github.com/dformoso/sklearn-classification/blob/master/Data%20Science%20Workbook%20-%20Census%20Income%20Dataset.ipynb

## Companion Mindmap/Cheatsheet
This Jupyter Notepad has a companion Mindmap/Cheatsheet that lists most of the Data Science steps that can be found at the following link:
- https://github.com/dformoso/machine-learning-mindmap

## Steps
In this Notebook, we'll perform:

- Feature Exploration (Uni and Bi-variate)
- Feature Imputation
- Feature Selection
- Feature Encoding
- Feature Ranking
- Machine Learning with sklearn and Tensorflow
- Random Search
- Accuracy, Precision, Recall, and f1 calculations
- ROC Curve

## Setup
This Notebook has been designed to be run on top of the Jupyter Tensorflow Docker instance found in the link below:
- https://github.com/jupyter/docker-stacks/tree/master/tensorflow-notebook

If you haven't downloaded Docker at this point, please visit:
- https://www.docker.com/get-docker

Then, open a shell or terminal session and copy/paste the following:

```shell
docker run -itd \
  --restart always \
  --name jupyter \
  --hostname jupyter \
  -p 8888:8888 \
  -p 6006:6006 \
  jupyter/tensorflow-notebook:latest \
  start-notebook.sh --NotebookApp.token=''
```

Upon running the command, docker will automatically pull the images it needs and get the containers going for us.

Give it a minute or so for Jupyter to start, and head to the following URL: http://localhost:8888

You should now have Jupyter running. If after a minute you can't reach the URL, check that the containers are running correctly and the network has been created by typing:

```shell
### Check the containers are running
docker ps -a
```
## Loading the Notebook
Download it from this link:
- https://github.com/dformoso/sklearn-classification/blob/master/Data%20Science%20Workbook%20-%20Census%20Income%20Dataset.ipynb

Go back to:
- http://localhost:8888, load your Notebook into Jupyter and run it. That's it!


## Troubleshooting Docker
Here's a few useful commands in case something goes wrong with your docker instance:

```shell
# Restart Jupyter Docker Container
docker restart jupyter

# Stop Jupyter Docker Container
docker stop jupyter

# Remove Jupyter Docker Container
docker rm jupyter
```

Feature Exploration (Uni and Bi-variate)
Feature Imputation
Feature Selection
Feature Encoding
Feature Ranking
Machine Learning Training
Random Search
Accuracy, Precision, Recall, and f1 calculations
ROC Curve

## Screenshots

### Feature Distribution Analysis
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/distribution.png)

### Feature Cleaning
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/cleaning.png)

### Missing Values is Features
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/missing.png)

### Bivariate Exploration
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/bivariate1.png)
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/bivariate2.png)

### Feature Correlation
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/correlation.png)

### Feature Importance
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/importance.png)

### Feature PCA
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/pca.png)

### Results from Machine Learning Algorithms
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/results.png)

### ROC for each Algorithm

![alt text](https://github.com/dformoso/sklearn-classification/blob/master/images/analysis.png)

## About Me
Twitter:
- https://twitter.com/danielmartinezf

Linkedin:
- https://www.linkedin.com/in/danielmartinezformoso/

Email:
- daniel.martinez.formoso@gmail.com
