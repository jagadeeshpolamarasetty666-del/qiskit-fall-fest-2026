# Qiskit Fall Fest 2026 — Quantum Computing Challenges

**Participant:** POLAMARASETTY JAGADEESH  
**Institution:** Vishnu Institute of Technology  
**Framework:** Qiskit 1.x & Qiskit Aer  

---

## 📌 Executive Summary

This repository contains the complete algorithmic designs, theoretical predictions, simulation experiments, and comparative analyses developed during the **Qiskit Fall Fest 2026** workshop. 

The project investigates fundamental quantum principles—ranging from single-qubit deterministic and superposition states to non-orthogonal state biasing and multi-qubit maximal entanglement/correlation switching. Each experiment combines step-by-step mathematical state vector analysis with empirical validation using the `AerSimulator` executed over 100 shots.

---

## 🧠 Key Quantum Concepts Mastered

Throughout this workshop and challenge series, the following principles were explored and implemented:

* **State Vector Rotations & Basis Inversion:** Analyzed the action of unitary Pauli-$X$ gates ($X = \begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$) to perform deterministic bit-flips and proved algebraic involution ($X^2 = I$).
* **Quantum Superposition & Born Rule Collapse:** Applied Hadamard gates ($H$) to generate uniform superposition states ($\vert{}+\rangle = \frac{\vert{}0\rangle + \vert{}1\rangle}{\sqrt{2}}$), demonstrating quantum indeterminacy and measurement collapse under shot noise.
* **Continuous State Biasing & Bloch Sphere Navigation:** Leveraged parameter-controlled unitary rotations ($R_y(\theta)$) to manipulate complex probability amplitudes ($\alpha\vert{}0\rangle + \beta\vert{}1\rangle$), constructing asymmetric quantum coins with arbitrary measurement likelihoods ($P(0) = \cos^2(\theta/2)$, $P(1) = \sin^2(\theta/2)$).
* **Entanglement & Bell States:** Engineered maximally entangled two-qubit pairs ($\vert{}\Phi^+\rangle = \frac{\vert{}00\rangle + \vert{}11\rangle}{\sqrt{2}}$) using controlled-NOT ($CNOT$) operations to observe non-classical correlations.
* **Correlation Switching & Parity Inversion:** Transformed correlated Bell states into anti-correlated Bell states ($\vert{}\Psi^+\rangle = \frac{\vert{}01\rangle + \vert{}10\rangle}{\sqrt{2}}$) via single-qubit localized Pauli operators without degrading mutual entanglement.

---

## 📂 Repository Contents

| Notebook | Focus Area | Circuit Design | Core Learning |
| :--- | :--- | :--- | :--- |
| **`Challenge_1.ipynb`** | State Initialization & Gates | Single-qubit with $X$, $X^2$, and $H$ gates | Predicted deterministic bit flips vs. probabilistic collapse; plotted 100-shot counts. |
| **`Challenge_2.ipynb`** | Quantum Coin Biasing | Single-qubit with parameterized $R_y(\theta)$ rotations | Controlled outcome distribution away from 50/50 using geometric Bloch sphere rotations. |
| **`Challenge_3.ipynb`** | Correlation Modification | Two-qubit Bell state ($H + CNOT$) + Local $X$ gate | Transitioned identical measurement pairs (`00`/`11`) to complementary pairs (`01`/`10`). |
| **`Challenge_4.ipynb`** | Correlation Switch | Two-qubit dual-circuit comparative design | Evaluated symmetric correlation vs. anti-correlation behavior using joint histograms. |
| **`Challenge_5.ipynb`** | Advanced Workshop Circuit | Multi-gate quantum logic workflow | Final capstone circuit synthesis and empirical validation. |

---

## 🛠️ Tools & Technologies

* **Language:** Python 3.11
* **Quantum Development Kit:** Qiskit 1.x
* **Simulator Backend:** Qiskit Aer (`AerSimulator`)
* **Visualization:** MatPlotLib, Qiskit Visualization Library (`plot_histogram`, `circuit_drawer`)
* **Environment:** JupyterLab / VS Code

---

## 🚀 How to Run the Notebooks Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/jagadeeshpolamarasetty666-del/qiskit-fall-fest-2026.git](https://github.com/jagadeeshpolamarasetty666-del/qiskit-fall-fest-2026.git)
   cd qiskit-fall-fest-2026
}
