# Introduction to Quantum Computing

A comprehensive, beginner-friendly course that takes you from "Hello World" to advanced quantum algorithms implemented in both **Qiskit (Python)** and **Q# (Microsoft)** for maximum learning.

## Course Structure

| Level | Topic | Qiskit | Q# |
|-------|-------|--------|-----|
| 1 | **The Quantum Awakening** — Setup & Hello World | [Notebook](Level_01_Quantum_Awakening/Level_01_Qiskit.ipynb) | [Notebook](Level_01_Quantum_Awakening/Level_01_QSharp.ipynb) |
| 2 | **The Single Qubit** — Bloch Sphere & Gates | [Notebook](Level_02_Single_Qubit_Bloch_Sphere/Level_02_Qiskit.ipynb) | [Notebook](Level_02_Single_Qubit_Bloch_Sphere/Level_02_QSharp.ipynb) |
| 3 | **Entanglement** — Multi-Qubit Systems & Bell States | [Notebook](Level_03_Entanglement/Level_03_Qiskit.ipynb) | [Notebook](Level_03_Entanglement/Level_03_QSharp.ipynb) |
| 4 | **Quantum Protocols** — Teleportation & Superdense Coding | [Notebook](Level_04_Quantum_Protocols/Level_04_Qiskit.ipynb) | [Notebook](Level_04_Quantum_Protocols/Level_04_QSharp.ipynb) |
| 5 | **Oracles** — Deutsch & Deutsch-Jozsa Algorithms | [Notebook](Level_05_Oracles_Deutsch_Jozsa/Level_05_Qiskit.ipynb) | [Notebook](Level_05_Oracles_Deutsch_Jozsa/Level_05_QSharp.ipynb) |
| 6 | **Grover's Algorithm** — Amplitude Amplification | [Notebook](Level_06_Grovers_Algorithm/Level_06_Qiskit.ipynb) | [Notebook](Level_06_Grovers_Algorithm/Level_06_QSharp.ipynb) |
| 7 | **Quantum Fourier Transform** — QFT & Inverse QFT | [Notebook](Level_07_QFT/Level_07_Qiskit.ipynb) | [Notebook](Level_07_QFT/Level_07_QSharp.ipynb) |
| 8 | **Phase Estimation & Shor's Algorithm** — Breaking RSA | [Notebook](Level_08_Phase_Estimation_Shor/Level_08_Qiskit.ipynb) | [Notebook](Level_08_Phase_Estimation_Shor/Level_08_QSharp.ipynb) |
| 9 | **NISQ Era** — Hybrid Algorithms (VQE / QAOA) | [Notebook](Level_09_NISQ_Hybrid/Level_09_Qiskit.ipynb) | [Notebook](Level_09_NISQ_Hybrid/Level_09_QSharp.ipynb) |
| 10 | **Error Correction** — Quantum Error Correction Codes | [Notebook](Level_10_Error_Correction/Level_10_Qiskit.ipynb) | [Notebook](Level_10_Error_Correction/Level_10_QSharp.ipynb) |

## Prerequisites

- Basic Python programming knowledge
- High school level math (linear algebra basics are taught along the way)
- Curiosity about quantum mechanics!

## Setup

### Option A: Qiskit (Python)

```bash
pip install qiskit qiskit-aer qiskit-visualization matplotlib pylatexenc
```

### Option B: Q# (Microsoft Quantum Development Kit)

```bash
pip install qsharp qsharp-widgets
```

### Option C: Both (Recommended!)

```bash
pip install qiskit qiskit-aer qiskit-visualization matplotlib pylatexenc qsharp qsharp-widgets
```

> **Note:** You'll also need [Jupyter Notebook](https://jupyter.org/install) or [VS Code](https://code.visualstudio.com/) with the Jupyter and Q# extensions.

## How to Use This Course

1. **Start at Level 1** and work your way up sequentially
2. **Read the theory sections** (markdown cells) before running code
3. **Run every code cell** — experiment by changing parameters!
4. Each level has **both a Qiskit and Q# version** — try both to see different perspectives
5. **Challenges** at the end of each notebook help reinforce learning

## Learning Path

```
Level 1-3:  FOUNDATIONS     → Qubits, gates, entanglement
Level 4-5:  PROTOCOLS       → Teleportation, oracles, interference
Level 6-8:  ALGORITHMS      → Grover, QFT, Shor
Level 9-10: CUTTING EDGE    → NISQ, VQE, error correction
```

## License

This educational material is provided for learning purposes. Feel free to use, modify, and share.

---

*"If you think you understand quantum mechanics, you don't understand quantum mechanics." — Richard Feynman*

*But by Level 10, you'll be closer than most!*
