# Quantum Circuit Project with Qiskit

## Project Overview

This project explores the creation and simulation of quantum circuits using Qiskit, a popular framework for quantum computing. The goal is to understand how quantum gates operate and how to manipulate qubits to achieve desired outcomes.

## How It Works

1. **Creating a Qubit Circuit**: 
   - A quantum circuit is initialized with a single qubit.
   - The circuit is visualized to understand its structure.

2. **Adding Measurement**: 
   - Measurement is incorporated to observe the qubit's state after operations.
   - The updated circuit is drawn to reflect these changes.

3. **Simulating the Circuit**: 
   - The circuit is simulated using Qiskit's AerSimulator.
   - Results are printed to show the measurement outcomes.

4. **Applying Quantum Gates**: 
   - The Pauli-X gate is applied to flip the qubit's state.
   - The Hadamard gate is used to create superposition, allowing the qubit to exist in both states simultaneously.

5. **Generating Arbitrary States**: 
   - The project demonstrates how to create arbitrary single-qubit states using rotation and phase gates.

6. **Comparing Probabilities**: 
   - Theoretical probabilities are compared with experimental results to illustrate the probabilistic nature of quantum measurements.

## Setup Instructions

To run this project, follow these steps:

1. **Install Python**: Ensure you have Python 3.x installed on your machine.

2. **Install Qiskit**: Use pip to install the Qiskit library:
   ```bash
   pip install qiskit
   ```

3. **Run the Jupyter Notebook**: 
   - Open the Jupyter Notebook where the project is saved.
   - Execute each cell sequentially to see the results and visualizations.

4. **Explore and Modify**: Feel free to modify the code to experiment with different quantum gates and circuits!

## Conclusion

This project provides a hands-on introduction to quantum computing concepts using Qiskit. By creating and simulating quantum circuits, you can gain insights into the fascinating world of quantum mechanics and computation.

## References

- [Qiskit Documentation](https://qiskit.org/documentation/)
- [Learn Quantum Computing](https://quantum-computing.ibm.com/docs/)