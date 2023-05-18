# Quantum Multiplier

This program takes two integers as an input, and display their product (multiplaction)
The implementation is based on Fourier basis addition and on this [papaer](https://arxiv.org/pdf/1411.5949v2.pdf).

# Functionality

The program synthesizes a specific quantum circuit appropriate for the integers (`number_1`, `number_2`) multiplication chosen, and runs it on a simulator (the default backend is `ibmq_qasm_simulator`, consisted of 32 qubits).
it is possible to enter integers with different bitstring lengths.
The size of the integers is limited by the specification of the backend that we run the circuit upon - The circuit is consisting of $2(n + m)$ qubits, while $n$ and $m$ are the lengths of the integers' bitstrings.

# Run
To run the simulation, clone and open this repo onto a jupyter notebook and run main.ipynb

## note: need to insert your ibm token onto ibm_token.txt before running 