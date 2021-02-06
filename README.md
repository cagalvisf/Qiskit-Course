# Qiskit Course Introduction to Quantum Computing and Quantum Hardware

This repository was made for the course Introduction to Quantum Computing and Quantum Hardware offered by IBM that you can find [here](https://qiskit.org/learn/intro-qc-qh/).
Here I am sharing my answers and points of view about the problems presented in the course and giving my solutions to them.

The course consist in a series of 9 lectures of approximately  2 hours each divided in different videos treating the following topics.

## 1. Introduction to Quantum Computing:
- ### 1.1 From bits to Qubits:
  This section introduces the notion of qubit. Besides that gives us the Dirac notation, explaining what is a ket and a bra and showing us how these can be seen as vectors. Then    gives us the notion of measurement as the probability of a superposed state to collapsed into one of the states that correspond to the basis in which we are making the measurement. Finally it is shown how all normalized and pure quantum states can be illustrated on the surface of a sphere of radius 1 called the Bloch Sphere.
### 1.2 Quantum Circuits:
Here we see the basic components of a circuit for 1 and 2 qubits. We can se some of the basic quantum gates for a single qubit such as the ones associated to the Pauli Matrices, Hadamard gate and different rotations as well as the controlled gates for a system of 2 qubits, in particular de CNOT gate. We use this in the qiskit library, learning how this gates modify the states.
### 1.3 Entanglement
Finally we have all the elements for defining the Bell states; these are associated to entangled states for 2 qubits. In this section we learn how to build up these states in terms of quantum gates and use them for making a teleportation protocol.
