# Animal Representation Learning Project

This repo contains code for a project of mine that trains animal classification models using different representation learning approaches.
These models are currently trained on the [cats vs. dogs](https://huggingface.co/datasets/cats_vs_dogs) dataset from HuggingFace.
I did this to learn more about computer vision, representation learning, and training models from scratch.

## Installation

The Animal Classifier has been tested using Python `3.9`.
If you are able to get this running on an older version of Python, or the Animal Classifier fails to run on a later version, please open an issue and I will look into it.

You can set up your Python envrionment using any method (e.g., Poetry, pipenv, conda, etc.), but please make sure you have **all** packages from `requirements.txt` installed. 

**NOTE**: I have tested this with `poetry` and included the relevant `poetry` files.
If you have success with other methods, please let me know and I can add instructions here!

## Scripts

There are two training scripts: `train_baseline.ipynb` and `train_matryoshka.ipynb`.
`train_baseline.ipynb` will train a baseline classification model and `train_matryoshka.ipynb` will train a classification model using Matryoshka Representation Learning.
