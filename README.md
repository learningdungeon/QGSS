# QGSS

# 🧪 Quantum Graduate Summer School (QGSS) – Lab Projects

This repository contains my completed labs from the **Quantum Graduate Summer School (QGSS)** program. These labs explore core concepts in quantum computing using Qiskit, covering foundational algorithms, quantum chemistry, and real-world optimization use cases. Each lab includes well-documented code, visualizations, and simulation results.

---

## 🔍 Lab Overview

| Lab | Title                                            | Focus Area                      |
|-----|--------------------------------------------------|----------------------------------|
| Lab 0 | Introduction to Quantum Circuits                | Quantum gates, measurement       |
| Lab 1 | Simulating Molecules with Quantum Chemistry     | Variational quantum eigensolver (VQE) |
| Lab 2 | Quantum Noise Mitigation                        | Measurement and readout error correction |
| Lab 3 | Grover’s Algorithm for Oracle Search            | Quantum search algorithm         |
| Lab 4 | Portfolio Optimization using QAOA               | Combinatorial optimization in finance |

---

## ⚙️ Lab Descriptions

### 🧱 Lab 0 – Introduction to Quantum Circuits

**Objective:**  
Get hands-on experience with quantum gates, superposition, and measurement on single- and multi-qubit systems.

**Highlights:**
- Basic gates: X, Y, Z, H, CX
- Bloch sphere visualization
- Entanglement and measurement outcomes
- Introduction to IBM quantum backends

---

### 🧪 Lab 1 – Quantum Chemistry: Simulating Molecules

**Objective:**  
Use Qiskit's chemistry module to simulate small molecules using the **Variational Quantum Eigensolver (VQE)**.

**Highlights:**
- Mapping molecular Hamiltonians to qubit operators  
- UCCSD ansatz  
- Finding ground state energies  
- Application to molecules like H₂ and LiH  

---

### 🛡️ Lab 2 – Quantum Noise Mitigation

**Objective:**  
Explore methods to mitigate quantum noise when running on real quantum hardware.

**Highlights:**
- Measurement error mitigation using calibration matrices  
- Readout error visualization  
- Running noisy vs. error-mitigated circuits on IBMQ backends  
- Discussing limitations of NISQ-era devices  

---

### 🔎 Lab 3 – Grover's Algorithm for Oracle Search

**Objective:**  
Demonstrate the use of **Grover’s Search Algorithm** to solve an unsorted database search problem using quantum oracles.

**Highlights:**
- Oracle and diffuser circuit construction  
- Amplifying the correct state  
- Measurement probabilities  
- Visualization of the solution state peak  

---

### 📊 Lab 4 – Portfolio Optimization using QAOA

**Objective:**  
Implement **Quantum Approximate Optimization Algorithm (QAOA)** to solve a simplified investment portfolio problem.

**Highlights:**
- Defining cost Hamiltonians  
- Using `qiskit_optimization` to model binary problems  
- QAOA ansatz building and parameter tuning  
- Simulating and comparing quantum results with classical solutions  

---

## 💻 Environment

- Framework: [Qiskit](https://qiskit.org/)
- Backend: IBM Quantum Experience (e.g., `ibm_brisbane`)
- Platform: qBraid / Local Python 3.11
- Visualization: Matplotlib, Qiskit tools

---

## 📁 Repository Structure

```bash
├── SuperPositionAndGates.ipynb
├── Grover_Search_Algo.ipynb
├── Qml.ipynb
├── Quantum_Error_Mitigation.ipynb
├── QAOA_Portfolio_Optimization.ipynb
├── RealDevice_BackendExecution.png
├── README.md
