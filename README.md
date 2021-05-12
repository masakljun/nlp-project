# Offensive language exploratory analysis

In this repository we provide the report and notebooks which we use to produce the results. Report is located in the main directory, figures of the report in *figs* directory, and notebooks and data in *code* directory.

## Requirements
To run the notebooks you will need to install the libraries that we use. The code was run on:
* python 3.7.10.

For BERT and USE embeddings you will also need a GPU and CUDA installed. We use:
* CUDA 11.1.

To install the required libraries we suggest you to install them from the *environment.yml* using Anaconda. If you prefer another option, feel free to use it. Note that the environment was tested with described libraries and version.

## Directory creation
Before running the notebooks, you should make sure to create the following directories if they not exist yet:
* code/data
* code/data/filtered
* code/datasets
* code/fastText

## Structure of notebooks
Notebooks are numbered in the order they should be run. Notebooks with same number can be run in arbitrary order.

When running the notebooks please make sure that you follow the instructions of where data should be located! Follow also other instruction written in the notebooks! When running fastText, make sure that you uncomment the line that downloads the model before trying to load the model!