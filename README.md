# UTokyo-Lecture-01

The repository is designated for the lecture in UTokyo.

To quickly start the tutorial, you can check the following details about installation of python and its necessary 
support environment, and make sure your python env is working on your laptop by setting up the correct environment variable. 

### Python installation 

You always have multiple choices to setup your python env and here I offer a light version of conda env with necessary 
components. Visit [miniconda homepage](https://docs.conda.io/en/latest/miniconda.html)
 to find the right version of your interest. 

- For Windows, [python 3.10](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)

- For MacOSX, [python 3.10](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh)

### Setup the conda environment

If you have installed the above conda package, you could firstly check if it's well installed by checking the following cmd:

```bash
conda --version  # and you will see the version info
```

If it does not work for your laptop, you can reboot your machine or simply check whether the installation procedure is correct. 

### Setup the python environment

There are many options to manage your python packages, e.g. `pip` or `pipenv`. Here, we take `pipenv` as the default package manager. 
Make sure your conda env has the right version of python and our required packages. Run the following code to install `pipenv`. 

```bash
conda create -n py39 python=3.9  # create a python env = 3.9
pip install pipenv  # install pipenv manager
```

Please also check the `Pipfile` and `Pipfile.lock` 
file in your root path. Run the following codes to sync your python env with us. 

```bash
pipenv install
```

### Use jupyter notebook to follow the tutorial

Replicable results are shown in the notebook named `tutorial.ipynb`. 
