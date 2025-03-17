# Anyon - SDT

## Summary

This project tackles a QUBO (Quadratic Unconstrained Binary Optimization) problem by QAOA (Quantum Approximate Optimization Algorithm), experimenting with **FOURIER heuristics (Discrete Fourier Transform on the classical paramters)** and a **custom tunable mixer Hamiltonian** to enhance optimization efficiency and adaptability for challenging, non-convex landscapes.

## Project structure:
/src_cudaq/ <br>
 ` `__init__`.py <br>
 ` circuits.py <br>
 ` fourier.py <br>
 ` optimizer.py <br>
 ` qaoa_converter.py <br>
 ` utils.py <br>
<br>
/src_pennylane/ <br>
  `__init__`.py <br>
  circuits.py <br>
  fourier.py <br>
  optimizer.py <br>
  qaoa_converter.py <br>
  utils.py <br>
<br>
QUBO_QAOA_cudaq.ipynb <br>
QUBO_QAOA_pennylane.ipynb <br>
requirements.txt <br>
README.md <br>

## Requirements:
pip install -r requirements.txt

## References

- Zhou, L., Wang, S.-T., Choi, S., Pichler, H., & Lukin, M. D. (2019). [Quantum Approximate Optimization Algorithm: Performance, Mechanism, and Implementation](https://arxiv.org/pdf/1812.01041.pdf). *arXiv preprint arXiv:1812.01041*.

- Actuaries UK. [Asset Liability Modelling in the Quantum Era](https://www.actuaries.org.uk/system/files/field/document/assetliability-modelling-in-the-quantum-era.%20to%20use.pdf).

- PennyLane. [QAOA Introduction Tutorial](https://pennylane.ai/qml/demos/tutorial_qaoa_intro).

- PennyLane. [QUBO Problem Tutorial](https://pennylane.ai/qml/demos/tutorial_QUBO).
