# CVON-AI Deep Artificial Network for Classification training project template
This repository contains a project template for training a deep learning network on cardiovascular imaging.
The project template is designed to work with cookiecutter, a python based tool that uses a project template
to install an setup your deep learning project. It works seemlessly with version control systems, such as
git and mercurial. 

## Getting started
You may choose different approaches to download and install the template.
Since cookiecutter works together with git and github, this git repository can be installed
using cookiecutter. However, it is a normal git repository. Therefore, you may also choose
to use git to clone the directory from your machine.

We encourage to use cookiecutter to install this template for a new project, because
cookiecutter will fill in the project details based on questions asked during installation. 
Variables, such as project name and author name will be injected into your project file and
directory structure.

### Installing cookiecutter
We strongly recommend the use of a separate python environment for the use of cookiecutter. 
Typically, this could be anaconda, or any python virtual environment you like. In the examples
below, we show two different approaches to setup a conda environment for cookiecutter:

```
# Create a conda environment:
conda create -n cookiecutter

# Activate the enviroment:
source activate cookiecutter

# Install cookiecutter:
conda install "cookiecutter>=1.7.0"
```

In the second approach, we use pip to install cookiecutter. However, we still use conda
to create a separate environment for the use of cookiecutter.
```
# Create a conda environment:
conda create -n cookiecutter

# Activate the enviroment:
source activate cookiecutter

# Install cookiecutter:
pip install "cookiecutter>=1.7.0"
```

### Using cookiecutter to install the image classification template
Assuming you have opted for a conda based installation of cookiecutter,
you may install the template as described below.

```
# Activate the enviroment:
source activate cookiecutter

cookiecutter https://github.com/CVON-AI/cvon-ai.training.image-classification
```