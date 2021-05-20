# Offensive language exploratory analysis

In this repository we provide the report and notebooks which we use to produce the results. Report is located in the main directory, figures of the report in *figs* directory, and notebooks and data in *code* directory.

## Requirements
To run the notebooks you will need to install the libraries that we use. The code was run on:
* python 3.7.10.

For BERT and USE embeddings you will also need a GPU and CUDA installed. We use:
* CUDA 11.1.

To install the required libraries we suggest you to install them from the *environment.yml* using Anaconda. If you prefer another option, feel free to use it. Note that the environment was tested with described libraries and version.

If you installed the libraries using Anaconda and *environment.yml*, you need to additionally install the *gensim* library.

## Data sets
Notebooks numbered *01_** to *03_** contain the code for the data set preparation. For you convenience some data sets are already extracted and located in the *code/data* folder. Note that some data sets require the agreement, and some data sets are data sets that require Twitter API key to be able to extract them. Each notebook describes what is required for the successful data extraction from various data sets, so that our work is fully reproducible.

However, as data extraction can be a long and tedious process, we provide you the extracted data, which can be used for running all notebooks from *04_** onward. Note that the data is password protected. You can obtain the password by contacting us at: *mt2421@student.fri.uni-lj.si* or *mk2700@student.uni-lj.si*. The data set is downloadable [HERE](https://drive.google.com/file/d/1T4gL4ftMv9EYCF0cX3hfU9AvlJFhXQ5i/view?usp=sharing).

The extracted dataset should be put in *code/dataset* folder and should be named *data.csv*. Note that notebooks *05_*, *06_*, and *10_* do not require the *data.csv* to be run. 

## Directory creation
Before running the notebooks, you should make sure to create the following directories if they not exist yet:
* code/data
* code/data/filtered
* code/datasets
* code/fastText

## Structure of notebooks
Notebooks are numbered in the order they should be run (01_* should be run before 02_*, etc.). Notebooks with same number can be run in arbitrary order.

When running the notebooks please make sure that you follow the instructions of where data should be located! Follow also other instruction written in the notebooks! When running fastText, make sure that you uncomment the line that downloads the model before trying to load the model!