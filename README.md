# Implementing a concept-level reference game with EGG

In this tutorial, you will learn how to implement a concept-level reference game with EGG. The concept-level reference game was used in publications and theses. It can be modified, adapted and extended depending on the specific research question. This notebook implements the baseline implementation and the context-aware vs. context-unaware training used in [Kobrock et al. (2024)](https://aclanthology.org/2024.lrec-main.339/). Note that the settings training, and analyses presented in this tutorial are the same as in the [emergent-abstractions main repository](https://github.com/kristinakobrock/emergent-abstractions/tree/main). However, for the sake of this tutorial, the code is simplified and only works for one run. Please use the training provided in the repository to make full use of the model. For the same reasons, this tutorial notebook is accompanied by simplied versions of the `archs.py` and `dataset.py`. These simplified versions can be used for the context-aware vs. context-unaware simulations. The [`emergent-abstractions`](https://github.com/kristinakobrock/emergent-abstractions/tree/main) repository contains many more settings, game configurations and analysis methods to choose from for more advanced users.

## Installing dependencies
We used Python 3.9.15 and PyTorch 1.13.0. Generally, the minimal requirements are Python 3.6 and PyTorch 1.1.0.
`requirements.txt` lists the python packages needed to run this code. Additionally, please make sure you install EGG following the instructions [here](https://github.com/facebookresearch/EGG#installing-egg).
1. (optional) Create a new conda environement:
```
conda create --name emergab python=3.9
conda activate emergab
```
2. EGG can be installed as a package to be used as a library (see [here](https://github.com/facebookresearch/EGG#installing-egg) for more options):
```
pip install git+https://github.com/facebookresearch/EGG.git
```
3. Install packages from the requirements file:
```
pip install -r requirements.txt
```

## Tutorial
Follow the [tutorial](https://github.com/kristinakobrock/tutorial-emergent-abstractions/blob/main/tutorial.ipynb) and let me know if you have any questions!
