# Graph neural networks for molecular graph classifcation

This is a respository to experiment with the data efficiency of various common GNN models (such as GCN, GAT, GraphSAGE, and GIN) on molecular graph classfication tasks. It utilizes the *[GraphGym](https://arxiv.org/abs/2011.08843)* platform to run and evaluate models.

## Datasets
So far experiments have been conducted using three different molecular graph datasets from the Open Graph Benchmark (OBG) collection. (1) `ogbg-molhiv` contains 41K molecules which are labeled according to their ability to inhibit HIV replication. (2) `ogbg-molbace` contains molecules which are labeled according to their ability to inhibit human beta-secretase 1. (3)`ogbg-molbbbp` contains molecules which are labeled according to their ability to cross the blood-brain barrier.

## Configuration
Experiment configurations are stored in the `/run` directory.
