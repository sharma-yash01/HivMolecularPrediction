# HivMolecularPrediction
Project to train model which predicts whether a molecule has the ability to inhibit HIV.

The Colab notebook can be found [here](https://colab.research.google.com/drive/1krCK8yhjONmVeUIz9pUY3MU3GTUlA4Fm?usp=sharing)

# Notebook's Introduction

Graph Neural Networks (GNNs) in the last few years have emerged as powerful tools for modeling complex, (semi-) structured, non-Euclidean data distributions. This has made them particularly well-suited for tasks such as molecular property prediction. This project focuses on leveraging a GNN to identify whether specific molecules, represented as graphs, have the potential to combat HIV. By treating molecules as graphs—with atoms as nodes and bonds as edges—the GNN can capture intricate relationships within the molecular structure.

As a Software Engineer at AWS Config, I've honed my skills in building secure cloud systems. In my tenure, I have also been at the forefront of integrating application-layer generative AI features into the service. This project showcases my ability to quickly adapt to emerging technologies and apply my diverse machine learning background, including research in Agro-AI, Differentiable Audition, and Differentiable Economics. In this Colab notebook, I'll delve into the application of graph transformers, demonstrating my proficiency in this rapidly evolving field.

In the following sections of this notebook, I will provide

1. An Overview of the dataset and the preprocessing steps undertaken to prepare the molecular graphs for training.
1. The Architectural details of the GNN model, including choice of layers and hyperparameters
1. Details on the training process designed, along with the evaluation metrics used to assess model performance.
1. Results, an analysis of model predictions, and an outline discussing future improvements to enhance the accuracy and applicability of the model.
1. A path to productionize the model on AWS
