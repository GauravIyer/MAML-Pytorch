# MAML-Pytorch
This is an easy-to-read, basic implementation of some of the supervised experiments in the paper titled "Model Agnostic Meta Learning for Fast Adaptation of Deep Networks" by Chelsea Finn et al. using PyTorch.

**Experiment 1**: Training a regression model on a sinusoidal function using MAML, and testing it on a new sinusoidal function, given a small number of samples of the new function.

**Experiment 2**: Training a Convolutional Neural Network on the Omniglot dataset to perform few shot classification. Evaluation is done using N way K shot classification.

**Note**: The code in this repository merely implements the experiments in the original paper. It does not replicate the results from the original paper as of now.

**Link to Omniglot Dataset**: https://github.com/brendenlake/omniglot

For training, the data in "images_background" is used.
For testing, the data in "images_evaluation" is used.
