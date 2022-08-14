# Artificial Neural Network for TGA
Artificial Neural Network for determining composition of plant biomass samples basing on thermogravimetric data.

## Project description
This tool is intend to support recognizing composition of plant biomass samples basing solely on thermogravimetric data (TG). The artificial neural network consists of three layers. First hidden layers has 11 nodes, and tangent sigmoidal output function. Second hidden layers had 16 nodes and radial basis transfer function. Output layers had 4 nodes and is pure linear. The schematic presentation is attached belowe:
<p align="center"><img src="https://github.com/kar-pos/TGA_ANN/blob/main/Source/ANN_topology.png" width=70% height=70%></p>

## Files description
* ANN_main.mlx - the file is general presentation of the tool. It includes visualization of the network, simple benchmark, and reference data presentation
* ANN_calc.mlx - this file has simply GUI for calculating the composition for user-defined samples
* ANN_trained.mat - in this file, the trained ANN is deployed. If you intend to use it in your own work, there is where you should start.
* Input_data.mat - learning/benchmark data set for the samples. The source of the data is avaible [here](https://github.com/kar-pos/TGA_ANN/tree/main/Source/TGA_data_source.pdf)
