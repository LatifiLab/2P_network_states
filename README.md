## 2P_network_states
This repository contains Jupyter notebooks to analyze the functional networks using 2-Photon Calcium imaging on different states collected in mouse.
This work will be submitted to: "State-dependent reorganization of functional network topology in mouse mesoscale cortical networks".

## Corresponding parts:
- [correlation and network](https://github.com/LatifiLab/2P_network_states/blob/main/correlation%20and%20network.ipynb) Modeling, calculating and statistical validation from 2p data to functional networks in three states.
- [plot_traces_network](./plot_traces_network.ipynb) Plot the heatmap traces and validated network.
- [modular features](./analyze_modularity.ipynb) Extract and compare modular features among status.
- [small-world features](./analyze_small worldness features.ipynb) Extract and compare small-world features, including small-world index, characteristic path length and clustering coefficient.
- [hub selection and features](./analyze_hub selection and features.ipynb) Identifying hub neurons and analyzing their features.
- [simulation parts](./simulation/) Containing simulations for the impact of negative edges on graph features and hub identification.

## Requirements:
The only specific Python packages that may require installment are:
- [Suite2p](https://github.com/MouseLand/suite2p) A widely-adopted Python package for 2P video processing, coregistration, deconvolution, and convert them into .npy files.
- [Networkx](https://github.com/networkx/networkx) A widely-adopted network analysis package, especially for small-world calculations.
Otherwise, all are usual Python packages that defaultly provided in Anaconda.
