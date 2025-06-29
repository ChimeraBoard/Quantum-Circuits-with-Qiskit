# Qubits and Classical Bits in Qiskit

# Quantum bits

In Qiskit:
- `QuantumRegister(1)` creates a register of 1 qubit.
- `qc = QuantumCircuit(1)` makes a circuit with one qubit.
- `qc = QuantumCircuit(1,1)` makes a circuit with one qubit and one classical bit.

Each qubit is shown as a **single horizontal wire** in the diagram.

# Classical Bits

Classical bits store the measurement outcomes of qubits.

- `ClassicalRegister(1)` creates a register of 1 classical bit.
- `qc.measure(qubit, classical_bit)` records the result.

In the visual representation:
- Qubits: one line per qubit
- Classical bits: often shown as **double lines**

