# Hybrid Quantum Neural Networks for Image Classification

## Overview
As we reach limits with classical compute power, it becomes necessary to investigate methods that execute faster and are capable of solving more difficult problems. By applying concepts from quantum mechanics to the computing space, we can leverage the power of superposition, entanglement, and interference to parallelize operations and operate at higher dimensions.

In this project, we compare classical machine learning with quantum machine learning through image-based car model classification algorithms. Specifically, our models predict vehicle make, model and year. This problem was chosen because it's already sufficiently difficult for a classic approach using convolutional neural networks, due to the minute level of detail a model would need to extract to differentiate between model years. Our goal with this project is to determine whether quantum-enhanced models can achieve performance comparable to or superior to classical approaches in the context of image classification.

## How to Use This Repository
First, create a Python virtual environment, activate it, and then run the following command.
```
python3 -m pip install -r requirements.txt
```
Note that `python3` might need to be changed to `py` or `python`, depending on your version.

`Stanford_Subset/augmented_quanvolution.ipynb` is the most recent version of the QNN simulation demo that models performance on a small subset of images from the Stanford Cars dataset. Run the cells in this notebook to simulate different configurations. There are adjustable parameters at the top of the notebook in the macros section. If trying to learn about quanvolutional layering or how the hybrid quantum neural network is supposed to perform in general, it is recommended that you start here. 

`VMMRdb_Stanford_Combined/Combined_ResNet_classic.ipynb` is the classical version of the model with the combined dataset. 

`VMMRdb_Stanford_Combined/Combined_ResNet_hqnn.ipynb` is the current version of the hybrid quantum neural network for the combined dataset. 


## Team Members
Olivia Watt

Lucas Shadoyan

Thomas Nguyen
