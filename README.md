# Dask Tutorial

## Prepare

You should clone this repository

    git clone http://github.com/dask/dask-tutorial

and then install necessary packages.

### a) Install into an existing environment

You will need the following core libraries

    conda install numpy pandas h5py Pillow matplotlib scipy toolz pytables snakeviz dask distributed

You may find the following libraries helpful for some exercises

    pip install graphviz cachey
    
### b) Create a new environment

In the repo directory

    conda env create -f environment.yml 

and then on osx/linux

    source activate dask-tutorial

on windows

    activate dask-tutorial



### Graphviz on Windows

Windows users can install graphviz as follows

1. Install Graphviz from http://www.graphviz.org/Download_windows.php
2. Add C:\Program Files (x86)\Graphviz2.38\bin to the PATH

Alternatively one can use the following conda commands (one installs graphviz and one installs python-bindings for graphviz):

1. conda install -c conda-forge graphviz
2. conda install -c conda-forge python-graphviz


### Launch notebook

From the repo directory

    jupyter notebook 
	
## Links

*  Reference
    *  [Docs](http://dask.pydata.org/en/latest/)
    *  [Code](https://github.com/dask/dask/)
