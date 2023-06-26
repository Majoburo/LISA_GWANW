# LISA-TUTORIAL
LISA tutorial for GWANW

## Google Colab version
[Click here to demo the notebook on Google Colab without installing anything.](https://colab.research.google.com/drive/1sZeciftJ8r6kDGYlfVlEkaf4FIAmx4mk?usp=sharing)

## Running locally
If you don't have Anaconda python installed, you should!

Download the installer [here](https://docs.conda.io/en/latest/miniconda.html), install it, and open a new terminal.

First we'll create a new python environment and install some dependencies, including the LISA Data Challenge tools:
```console
$ conda create -n lisa-tut python=3.9 numpy scipy matplotlib gsl fftw
$ conda activate lisa-tut
$ pip install astropy eryn chainconsumer lisa-data-challenge jupyter
```

Download this repo and `cd` into the folder.
Then we can open the tutorial notebook with `jupyter notebook`

If you want to run any of the MCMC inference cells, you can set the variables `download_results` to `False`
