# Inorganic Computational Chemistry Project

A hands‑on collection of Jupyter notebooks exploring foundational topics in inorganic computational chemistry using the [Atomic Simulation Environment (ASE)](https://wiki.fysik.dtu.dk/ase/). This project covers:

- Inorganic complexes  
- Molecular and crystal symmetry  
- Properties and applications of crystalline solids  
- Nanoparticles and solid surfaces  
- Applications of surfaces in catalysis  

---

## Table of Contents

1. [Prerequisites](#prerequisites)  
2. [Conda Environment Setup](#conda-environment-setup)  
3. [Installing ASE](#installing-ase)   
6. [Acknowledgements](#acknowledgements)  

---

## Prerequisites

- **Python** ≥ 3.8  
- **Git** (for version control)  
- **Conda** (Miniconda or Anaconda distribution)  

---

## Conda Environment Setup

Create and activate a dedicated environment for this project:

```bash
# Create environment named 'chem'
conda create -n chem python=3.9
conda activate chem
```

## Installing ASE

The Atomic Simulation Environment (ASE) is a Python library for setting up, manipulating, running, and analyzing atomistic simulations. See full documentation at the ASE wiki.

#### On Linux

```bash
# Using conda-forge
conda install -c conda-forge ase

# Or with pip
pip install ase
```

#### On Windows

```bash
# In Anaconda Prompt
conda install -c conda-forge ase

# Or with pip
pip install ase
```

## Additional Requirements

ASE relies on standard scientific Python packages. Install as needed:

```bash
pip install numpy scipy matplotlib ipython
# Optional: spglib for advanced symmetry analysis
pip install spglib
```
### Acknowledgements

This README and project scaffold were generated with assistance from OpenAI’s ChatGPT.
Special thanks to the ASE development team for the [Atomic Simulation Environment](https://wiki.fysik.dtu.dk/ase/).
