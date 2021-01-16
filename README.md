## Overview
We provide jupyter notebooks that contain a step-by-step process to reproduce experimental results. Please ensure that the values for data directories (data.py) and model directories (jupyter notebooks) have been set correctly. Follow DAE-MNIST.ipynb to reproduce MNIST results, DAE-CelebA to reproduce CelebA results, and DAE-plots.ipynb to reproduces images / plots in the paper.  


## Requirements
* python: 2.7.16
* ipython: 5.8.0 
* ipython_genutils: 0.2.0
* keras: 2.2.0
* tensorflow: 1.10.0
* PIL: 6.2.0
* matplotlib: 2.2.3
* imageio: 2.6.0

## Structure
* DAE-MNIST.ipynb: Code to reproduce MNIST recovery results. **Modify path to load/save model**.
* DAE-CelebA.ipynb: Code to reproduce CelebA recovery results. **Modify path to load/save model**.
* DAE-plots.ipynb: Code to reproduce images / plots in the paper. **Modify paths to load data**.
* data.py: pre-processing / loading data. **Modify default data path for CelebA**.
* models_def.py: defintion of model architectures used in the paper.
* utils.py: core recovery algorithm code and util functions for super-resolution and inpainting.
* models.zip: pre-trained models used for the paper. 
* celebAtest.zip: CelebA test data used for the paper.
* mnisttest.zip: MNIST test data used for the paper. 
