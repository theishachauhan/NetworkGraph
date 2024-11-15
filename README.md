PathFinder: Gradient Descent in Dynamic Graph Networks
This project explores the behavior of gradient descent algorithms for pathfinding in dynamic graph networks. The focus is on evaluating the impact of node connectivity and network uncertainty on algorithm performance.

Files Overview
graph_gen.ipynb
Contains graph generation functions for creating synthetic networks. Customize the graph properties (e.g., number of nodes, edge probabilities) and select the desired function for experimentation.

PathFinder.ipynb
Implements the project workflow. This includes:

Loading graphs from graph_gen.ipynb.
Applying gradient descent algorithms (SGD, Adam, RMSprop, etc.) to find optimal paths.
Visualizing results, including paths, convergence, and loss functions.
How to Use
Open graph_gen.ipynb to generate a graph. Adjust the parameters as needed.
Save the generated graph and load it into PathFinder.ipynb.
Run PathFinder.ipynb to analyze the performance of gradient descent algorithms and visualize outcomes.
Key Features
Customizable graph generation.
Evaluation of pathfinding performance under varying edge probabilities and node counts.
Visual comparison of algorithms with detailed metrics.
