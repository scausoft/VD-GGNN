# Vulnerability Detection in Smart Contracts Based on Gate Graph Neural Network
This repo is a python implementation of vulnerability detection in smart contracts based on gate graph neural network.

# Dataset
To run experiments on this task, you need to download the data from https://docs.google.com/spreadsheets/d/17QxTGZA7xNifAV8bQ2A2dJWRRHcmPp3QgPNxwptT9Zw/edit#gid=836095968 and https://github.com/Messi-Q/Smart-Contract-Dataset. 

# Running
To train a model, it suffices to run `python train.py MODEL_TYPE TASK`, for
example as follows:
```
$ --data-path data/my ggnn CitationNetwork --tensorboard logdir

The implementation of the GGNN model is based on https://github.com/microsoft/tf-gnn-samples.


