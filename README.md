# AmnesiacML

Laura Graves, Vineel Nagisetty, Vijay Ganesh

This repo includes two methods for removing learned data from a neural network. 

**Unlearning** involves retraining on a modified dataset that is designed to muddy the model's understanding of sensitive data

**Amnesiac Unlearning** involves specific removal of the learning from batches containing sensitive data

These methods were evaluated via test accuracy, membership inference attacks, and model inversion attacks.

Amnesiac ML Evaluation.ipynb contains a notebook that tests the effect of greater levels of amnesiac unlearning on model efficacy.

Membership Inference Attack.ipynb contains a notebook that runs a Membership Inference Attack on a resnet18 model trained on CIFAR100, and evaluates the success of this attack against amnesiac unlearning.

Model Inversion Attack.ipynb contains a notebook that runs a Model Inversion Attack against a trained PyTorch model.

Amnesiac Machine Learning.pdf is a preprint paper containing our research findings and a detailed description of methods and evaluation.