# Quantum Key Distribution Simulator

## Overview
This repository contains a Python simulation of the BB84 Quantum Key Distribution (QKD) protocol. 
The project is designed to demonstrate how quantum mechanics can be used to securely distribute cryptographic keys. 
This simulator uses Qiskit, a framework for quantum computing, to create and visualize quantum circuits that implement the BB84 protocol.


## Installation
To run this simulation, you need Python and the following packages:
- `numpy`
- `qiskit` 
- `qiskit-aer`
- `IPython`
- `matplotlib` (optional for additional plotting functionality)
- `pylatexenc` (needed for matplotlib)


### Setting Up Your Environment
1. Ensure you have Python installed. Python 3.8 or later is recommended.
2. Install the required packages using pip:
   ```bash
   pip install numpy qiskit matplotlib IPython qiskit-aer pylantexenc

### Cloning the Repository
git clone https://git.txstate.edu/cac570/CS4371.git


## Running the Simulation

### Using Jupyter Notebook
Ensure you have Jupyter Notebook installed. 
If not, you can install it via pip:
pip install notebook

To launch the notebook:
jupyter notebook BB84.ipynb

### For Ubuntu users
sudo apt update
sudo apt install python3-pip python3-dev
pip3 install notebook numpy qiskit matplotlib IPython

To launch:  jupyter notebook BB84.ipynb


## Functionality
   - The simulation visualizes the creation of qubits, the process of eavesdropping, and the sifting of a quantum key.
   - It correctly handles quantum superpositions and measurements according to the BB84 protocol.
   - Error detection through eavesdropping is simulated and visualized.


### What's Not Covered
The simulation does not implement error correction and privacy amplification which are part of a full QKD system.


### Data for Testing
The repository includes test data in the form of pre-configured settings in the script to simulate different scenarios of quantum communication and eavesdropping.


### Scholarly References
Foundational Research: Bennett, C. H., & Brassard, G. (1984). Quantum cryptography: Public key distribution and coin tossing. In Proceedings of IEEE International Conference on Computers, Systems and Signal Processing (pp. 175–179). IEEE.

Contemporary Research: Wang, Q., Xu, F., Zhao, Y., & Lo, H.-K. (2023). Enhancing the security of quantum key distribution with basis mismatched events. Physical Review Research, 5(2), 023065.


### Conclusion
This project demonstrates a practical application of quantum mechanics in the field of secure communications.
It highlights both the potential and current limitations of implementing quantum cryptographic protocols in real-world scenarios.

