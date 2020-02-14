# 2020-Real-Conda-Cheat-Sheet

There are too many conda cheat sheet out there that give too much info but lack of the most important tips.

The intention of this repo is to give you the most important steps to set up an Anaconda environment in various OSs with best practices, so that you don't have to deal with some of the common pitfalls and countless hours searching for a solution.

## How to create an conda environment correctly in Windows

- basic commands

```python

# this is basic command to install the most common packages in anaconda
conda create -n [your environment name] python=3.7 anaconda

# this command install all available virtual env in jupyter notebook ipython kernels
conda install -y nb_conda_kernels

# this command install a new conda tab in jupyter environment
conda install -y nb_conda

# this list all available conda environment
conda env list

# to list all kernels listed in jupyter notebook
jupyter kernelspec list

# to remove a orphened (deleted) environment from jupyter notebook
jupyter kernelspec uninstall [unwanted-kernel]

# or you can use remove
jupyter kernelspec remove [unwanted-kernel]

```
