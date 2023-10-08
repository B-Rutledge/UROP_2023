# UROP_2023
Final Scripts that were developed as part of my research placement at Imperial College London under the supervision of Prof. Rafael Palacios.
The goal was to use a graph neural network to predict the dynamics of a slender wing.

This was partly inspired by work done by AIRBUS (refer to https://github.com/mid2SUPAERO/GNN4HALE/tree/main)

The graph neural network was built using GraphNets developed by Google-Deepmind (refer to https://github.com/deepmind/graph_nets)

The training data was obtained via SHARPy (refer to https://github.com/ImperialCollegeLondon/sharpy).

To use these scripts do the following. First open the 'SHARPy data collection' folder and run the script inside (with a SHARPy environment) to collect simulations. These will be placed into the 'output' folder. Second, copy all of the outputs into the 'Data' folder. Third run the 'Prismatic Wing Basic' script (with a GraphNet environment) to train a graph neural network.
