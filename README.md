# Bayesian Machine Learning in Julia

## About

Implementing Bayesian Logistic Regression from first principles in Julia : from assumptions, to mathematics to code. I use a Jupyter Notebooks to analyse and pre-process an open datasets, and then train and test my model on it. For personal research and self-learning, but it might be useful for anyone trying to dig deeper into Bayesian ML.


## Methods 

I employ and End to End Machine learning workflows, with the following stages in mind :

- Analyse and understand the data.
- Transform the data to be processed by ML algorithms.
- Implement a Bayesian Logistic Regression from scratch, understanding the mathematics behind it. 
- Compare accuracy on the test set with ready-to-use packages/

## Technology

- All the code is in **Julia 1.9.3**
- I make use of various packages in *Julia*, for the full list please the the Jupyter notebooks.


Once you install Julia locally and set-up the Jupyter Notebook, you can simply install packages with two lines of code, directly from the notebook : 

using Pkg
Pkg.add("NameOfPackage")

For example, to install DataFrames :

using Pkg
Pkg.add("DataFrames")

