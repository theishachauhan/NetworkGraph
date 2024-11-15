PathFinder: Gradient Descent in Dynamic Graph Networks

This project explores the behavior of gradient descent algorithms for pathfinding in dynamic graph networks. The focus is on evaluating the impact of node connectivity and network uncertainty on algorithm performance.

**Files Overview**
> _graph_gen.ipynb_

Contains graph generation functions for creating synthetic networks. Customize the graph properties (e.g., number of nodes, edge probabilities) and select the desired function for experimentation.

> _PathFinder.ipynb_

Implements the project workflow, i.e. Applying gradient descent algorithms (SGD, Adam, RMSprop, etc.) to find optimal paths. Visualizing results, including paths, convergence, and loss functions.

**How to Use :**
- Open graph_gen.ipynb to generate a graph. Adjust the parameters as needed.

- Select the graph function and paste it into PathFinder.ipynb graph generator function.

- Run PathFinder.ipynb to analyze the performance of gradient descent algorithms and visualize outcomes.

**Key Features**
Customizable graph generation, Evaluation of pathfinding performance under varying edge probabilities and node counts,  Visual comparison of algorithms with detailed metrics.
