# Advanced Theoretical Physics Manuscripts

[![Repository](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/Leo-ChengXuLiu/Advanced-Theoretical-Physics-Manuscripts)
[![Language](https://img.shields.io/badge/Language-Jupyter%20Notebook-blue)](https://github.com/Leo-ChengXuLiu/Advanced-Theoretical-Physics-Manuscripts)

A curated collection of advanced theoretical physics manuscripts, rigorous mathematical derivations, and computational demonstrations. This repository bridges the gap between **analytical textbook physics** (with a focus on Sakurai's *Modern Quantum Mechanics* and Landau's *Theoretical Physics*) and **numerical intuition** through interactive code.

---

## 🧠 Theoretical Derivations & Handwritten Manuscripts

A core component of this repository is the meticulous, step-by-step derivation of advanced quantum and classical mechanics concepts. Rather than just presenting final formulas, I focus on the underlying mathematical physics, exploring the nuances of operator formalism, quantum dynamics, and state evolution.

Below are selected excerpts from my handwritten manuscripts, showcasing detailed analytical derivations:

<p align="center">
  <img src="Sakurai_quantum/Handwritten%20img/Quantum_1_preview.jpg" width="45%" alt="Quantum Mechanics Derivation 1">
  &nbsp; &nbsp;
  <img src="Sakurai_quantum/Handwritten%20img/Quantum_2_preview.jpg" width="45%" alt="Quantum Mechanics Derivation 2">
</p>
<p align="center">
  <img src="Sakurai_quantum/Handwritten%20img/Landao_1_preview.jpg" width="45%" alt="Landau Mechanics Derivation 1">
  &nbsp; &nbsp;
  <img src="Sakurai_quantum/Handwritten%20img/Landao_2_preview.jpg" width="45%" alt="Landau Mechanics Derivation 2">
</p>

---

## 💻 Interactive Computational Demonstrations

To complement the analytical derivations, I am developing a series of **interactive Jupyter Notebooks**. These serve to translate abstract quantum theory into manipulable, visual, and reproducible computational experiments.

### ✨ Highlight: Interactive Coherent State (Sakurai)
I have recently added a comprehensive interactive demonstration of **Coherent States**, inspired by Sakurai's treatment of the quantum harmonic oscillator. 

<p align="center">
  <img src="Sakurai_quantum/Handwritten%20img/Coherent_1.png" width="80%" alt="Coherent State Preview">
</p>

**Features of this module:**
- **Parameter-Tunable Exploration:** Users can dynamically adjust eigenvalues ($\alpha$) and time-evolution parameters to observe wave packet behavior.
- **Visualizing Quantum Dynamics:** Real-time plotting of probability densities and phase space trajectories.
- **Bridging Math and Code:** The numerical implementation directly mirrors the analytical derivations presented in my handwritten notes.

**Future Updates:**  
I am actively developing and will continue to upload more interactive demonstrations (e.g., Spin Dynamics, Time-Dependent Perturbation Theory, and Path Integrals) to expand this computational physics suite.

---

## 📁 Repository Structure

```text
.
├── Sakurai_quantum/
│   ├── Interactive Jupyternotebook/     # Interactive Python demos
│   ├── Handwritten img/                 # Analytical derivations & previews
│   └── Sakurai-Quantum.pdf              # Core reference text
├── Landao_mechanics/
│   └── ...
└── README.md
```

---

## 🚀 Running the Interactive Notebooks

If you would like to run the computational demonstrations locally:

### 1. Clone the repository
```bash
git clone https://github.com/Leo-ChengXuLiu/Advanced-Theoretical-Physics-Manuscripts.git
cd Advanced-Theoretical-Physics-Manuscripts
```

### 2. Install Requirements
The notebooks utilize standard scientific computing libraries.
```bash
pip install numpy matplotlib ipywidgets notebook
```

### 3. Launch Jupyter
```bash
jupyter notebook
```
Navigate to `Sakurai_quantum/Interactive Jupyternotebook/` to explore the interactive code.

---

## 🤝 About & Contact

This project serves as both a **personal academic portfolio** and an **open educational resource** for students and researchers interested in computational and theoretical physics. 

Whether you are reviewing my application, looking for pedagogical tools in quantum mechanics, or interested in scientific computing, feel free to explore the repository.

**Maintainer:** [Leo-ChengXuLiu](https://github.com/Leo-ChengXuLiu)
