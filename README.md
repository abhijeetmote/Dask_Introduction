dask Tutorial
Prepare
You should clone this repository
https://github.com/abhijeetmote/Dask_Introduction

and then install necessary packages.

Install into an existing environment
You will need the following core libraries

conda install numpy pandas h5py Pillow matplotlib scipy toolz pytables snakeviz dask distributed
You may find the following libraries helpful for some exercises

pip install graphviz cachey


Graphviz on Windows
Windows users can install graphviz as follows

Install Graphviz from http://www.graphviz.org/Download_windows.php
Add C:\Program Files (x86)\Graphviz2.38\bin to the PATH
Alternatively one can use the following conda commands (one installs graphviz and one installs python-bindings for graphviz):

conda install -c conda-forge graphviz
conda install -c conda-forge python-graphviz

Launch notebook
From the repo directory
jupyter notebook 
