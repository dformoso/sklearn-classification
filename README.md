# Census Income Dataset Classification
Data Science Notebook on a Classification Task

## Objective
In the Jupyter Notepad included in this page, we will using the Census Income Dataset to predict whether an individual's income exceeds $50K/yr based on census data.

The Dataset can be found here: https://archive.ics.uci.edu/ml/datasets/adult

The Notepad can be found here: https://github.com/dformoso/sklearn-classification/blob/master/Data%20Science%20Workbook%20-%20Census%20Income%20Dataset%20-%20v2.ipynb

## Steps
In this Notepad, we'll perform:

- Feature Exploration (Uni and Bi-variate)
- Feature Imputation
- Feature Selection
- Feature Encoding
- Feature Ranking
- Machine Learning Training 
- Random Search
- Accuracy, Precision, Recall, and f1 calculations
- ROC Curve
 
## Setup
This Notepad has been designed to be run on top of the Jupyter Tensorflow Docker instance found in the link below: 
- https://github.com/jupyter/docker-stacks/tree/master/tensorflow-notebook

If you haven't downloaded Docker at this point, please visit: 
https://www.docker.com/get-docker

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
### Check the User Defined network has been created and containers are running
docker ps -a
```
## Loading the Notebook
It's now time to download the Notebook...!

Download it from this link:
- https://github.com/dformoso/sklearn-classification/blob/master/Data%20Science%20Workbook%20-%20Census%20Income%20Dataset%20-%20v2.ipynb

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

### Distribution Analysis
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/distribution.png)

### Cleaning
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/cleaning.png)

### Missing Values
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/missing.png)

### Bivariate Exploration
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/bivariate1.png)
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/bivariate2.png)

### Feature Correlation
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/correlation.png)

### Feature Importance
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/importance.png)

### Feature PCA
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/pca.png)

### Results 
![alt text](https://github.com/dformoso/sklearn-classification/blob/master/results.png)

### ROCs

![alt text](https://github.com/dformoso/sklearn-classification/blob/master/analysis.png)

## About Me
https://www.linkedin.com/in/danielmartinezformoso/

