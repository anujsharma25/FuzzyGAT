
# FuzzyGAT Operator

A novel Graph Neural Network (GNN) operator that integrates **Fuzzy Logic** into the **Graph Attention Network (GAT)** framework to enhance reasoning under uncertainty, noise, and sparse data environments. This project implements the fuzzy-based GAT operator for improved node classification, graph classification, and representation learning tasks.

## Overview

Conventional GATs leverage attention mechanisms to weigh neighboring nodes, but may struggle in uncertain or ambiguous graph structures. To address this, our **Fuzzy GAT Operator** introduces:

- Fuzzy membership functions for attention coefficient computation.
- Adaptive reasoning over imprecise or noisy relationships.
- Improved interpretability and robustness over standard GATs.

This repo contains:
- PyTorch-based implementation of the fuzzy GAT operator.
- Integration with PyTorch Geometric (PyG).
- Training and evaluation scripts on benchmark datasets (e.g., Cora, Citeseer, Pubmed).



