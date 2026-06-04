# Machine Learning-based Quantum Error Mitigation for Variational Algorithms

Machine Learning-based Quantum Error Mitigation (ML-QEM) has emerged as a promising approach for improving the performance of noisy quantum algorithms. However, existing ML-QEM methods often have restricted applicability to variational circuits and rely on inaccessible noiseless training data. In this work, we propose a practical ML-QEM protocol tailored to variational quantum algorithms, which generates training data by simulating (near-)Clifford circuits. This data is used for model selection and training, producing a mitigation model that can correct variational circuits with arbitrary parameters and transfer across different target Hamiltonians of similar structure. We benchmark the proposed method on the Variational Quantum Eigensolver (VQE) task for the Sherrington-Kirkpatrick Hamiltonian of up to $n=12$ qubits under various noise models, analyzing its effect on trainability and comparing its performance against standard Zero-Noise Extrapolation (ZNE). The results demonstrate consistent several-fold error suppression across all tested settings and superior performance over ZNE in the high-noise regime, providing evidence for the applicability of the proposed protocol to present-day NISQ processors.

The repository contains the numerical simulations for the paper https://arxiv.org/abs/2606.02697.

## Citation
If you use the numerical results in this repository, please cite the following paper:

```bibtex
@misc{korolev2026machinelearningbasedquantumerror,
      title={Machine Learning-based Quantum Error Mitigation for Variational Algorithms}, 
      author={Nikita Korolev and Kirill Lakhmanskiy and Daniil Rabinovich},
      year={2026},
      eprint={2606.02697},
      archivePrefix={arXiv},
      primaryClass={quant-ph},
      url={https://arxiv.org/abs/2606.02697}, 
}
