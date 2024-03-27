Project proposal
Relation Prediction in Knowledge Graphs

team ‘Graph lovers’:
Lobachev Nikita
Azevich Mark
Ozerova Daria

Functionality:
For this project, we will be tackling the general ML problem of relation prediction in knowledge graphs. Specifically, we will focus on link prediction in heterogeneous graphs. The goal is to predict missing relationships between entities in a knowledge graph. We will explore different techniques and models to improve the accuracy of these predictions.
To address this problem, we will cover PyG functionalities such as Graph Convolutional Networks (GCNs), Graph Attention Networks (GATs). These modules provide powerful tools for modeling graph data and extracting meaningful features from the graph structure. We will also explore different loss functions and evaluation metrics to measure the performance of our models.

Demonstration:
To concretely demonstrate these functionalities, we will use a popular knowledge graph dataset WikiGraphs. WikiGraphs is a dataset of Wikipedia articles each paired with a knowledge graph, to facilitate the research in conditional text generation, graph generation and graph representation learning. Existing graph-text paired datasets typically contain small graphs and short text (1 or few sentences), thus limiting the capabilities of the models that can be learned on the data. We will preprocess the dataset to create a heterogeneous graph representation using PyG's data handling utilities.

In the ML pipeline, we will walk through the following steps:
1. Data Loading and Preprocessing: We will load the knowledge graph dataset into PyG and preprocess it to create node and edge features.
2. Model Definition: We will define a GCN or GAT model architecture using PyG's built-in classes for graph neural networks.
3. Training and Evaluation: We will train the model on the knowledge graph data and evaluate its performance using metrics like Mean Reciprocal Rank (MRR) or Hits@k.
4. Hyperparameter Tuning: We will explore different hyperparameters and optimization techniques to improve the model's performance.
5. Inference: Finally, we will use the trained model to make predictions on unseen data and analyze the results.
By walking through these steps, we aim to showcase how PyG functionalities can be leveraged to address the problem of relation prediction in knowledge graphs effectively.




