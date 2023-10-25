# 4-QubitGrover
Project for the Quantum Simulation Exam, in which I implemented a 4 qubit Grover algorithm 

In this repositery I studied the Grover’s search algorithm, which is one of the most popular quantum computing algorithms. It can search for an entity with high probability in an unstructured list using only O(√N).
Grover’s Search Algorithm was developed by Grover in 1996, and has the objective of searching for an object in an unstructured data array of N items.
This project is divided in two main parts.
The first is related to the study of the algorithm implemented in both a 3 and 4 qubit scenario.
The second part was related to the application of a measurement-error mitigation technique. The objective is to reduce measurement errors by applying measurement error mitigation to the Grover Algorithm itself.

## First results
The Grover Algorithm was implemented using three qubits and two iterations.
This circuit has been studied both using the simulator and using the LIMA quantum computers.
In the same framework I implemented a 4 qubit Grover circuit and performed the same analysis

## Second results
The new objective is to perform measurement error mitigation to improve the results found in the case of the 4 qubit implementation.
The error correction has been applied using the Calibration Matrix and the data available from IBM


All the details related to the project with a better explanation and all the plots are available on the report that is uploaded in this repository
