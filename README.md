# Spiking-Neural-Network-Synapses-Simulation
This project focuses on the implementation and analysis of synaptic models and connectivity schemes in neural networks using Python

The project explores the Dirac Delta function and conductance-based models for synapse implementation and tests various connectivity schemes, such as full connectivity, random coupling with fixed coupling probability, and random coupling with a fixed number of presynaptic partners.

## Project Objectives
1. **Synapse Implementation**: Implement synapses using the Dirac Delta function and conductance-based models to simulate synaptic transmission in neural networks.
2. **Connectivity Schemes**: Explore different connectivity patterns, including full connectivity, random coupling with fixed probability, and fixed presynaptic partners, to understand their impact on neural network dynamics.
3. **Neuronal Response Analysis**: Test the response of neurons to constant current input with and without noise, and analyze the resulting membrane potential, current, and spike generation.

## Implemented Features
### 1. Synapse Models
- **Dirac Delta Function**: Models instantaneous synaptic transmission with an impulse response.
- **Conductance-Based Model**: Simulates synaptic transmission using an exponential decay function to model ion flow across the synaptic membrane.

### 2. Connectivity Schemes
- **Full Connectivity**: Every neuron is connected to every other neuron in the network, promoting synchronized network activity.
- **Random Coupling with Fixed Coupling Probability**: Neurons are connected randomly based on a fixed probability, leading to a sparse and robust network structure.
- **Random Coupling with Fixed Number of Presynaptic Partners**: Each neuron receives input from a fixed number of randomly selected presynaptic partners, balancing connectivity and network sparsity.

### 3. Neuronal Response Testing
- **Constant Current Input**: Simulates neuronal behavior under a constant current with and without noise to study the impact on membrane potential and spike generation.
- **Homogeneous Neuron Populations**: Analyzes the dynamics of excitatory and inhibitory neuron populations when exposed to random input currents.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `random`, `scipy`, `PymoNNtorch`
