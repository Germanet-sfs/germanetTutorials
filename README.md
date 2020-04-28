# GermaNet Tutorials

This repository contains two tutorials that show how to use the Java-- and the Python API for GermaNet. [GermaNet](https://uni-tuebingen.de/de/142806) is a lexical semantic network that partitions the lexical
space in a set of concepts that are interlinked with semantic relations.

The tutorial for the Java API is located in the [javaAPI](https://github.com/Germanet-sfs/germanetTutorials/tree/master/javaAPI) directory. The Java API is located [here](https://github.com/Germanet-sfs/GermaNetApi)

The tutorial for the Python API is located in the [pythonAPI](https://github.com/Germanet-sfs/germanetTutorials/tree/master/pythonAPI) directory. The Python API can be found [here](https://github.com/Germanet-sfs/germanetpy).


## Install jupyter
The tutorials are provided as interactive jupyter notebooks. That means that you can read the tutorial and run the code snippets in your browser or programming enviroment. You can also change parts of the code and adapt it to your fulfill your purposes.
Alternatively you can just read the tutorial online without being able to run the code interactively.

To be able to run the tutorial as a jupyter notebook you have to install jupyter, which can be done with pip:
```
pip install jupyterlab
```
or with conda:
```
conda install -c conda-forge jupyterlab
```
more detailed information about jupyter can be found [here](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

## Java API Tutorial

To be able to use the java tutorial with jupyter you additionally have to install the *ijava* kernel with jupyter as it is not included in the default installation. To install it, follow the instructions under *requirements* and *installing* on [this page](https://github.com/SpencerPark/IJava#requirements).

Once you successfully installed the kernel, clone this repository to your local machine and cd into the javaAPI directory:
```console
cd germanetTutorials/javaAPI
```

There you can enter 
```
jupyter notebook
```
This should open a new window in your default browser where you can see the tutorial within the jupyter enviroment. Click on it to browse it and run the code.

## python API tutorial
Clone this repository to your local machine and cd into the pythonAPI directory:
```console
cd germanetTutorials/pythonAPI
```
There you can enter 
```
jupyter notebook
```
This should open a new window in your default browser where you can see the tutorial within the jupyter enviroment. Click on it to browse it and run the code.
