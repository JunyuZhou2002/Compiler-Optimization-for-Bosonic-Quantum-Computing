# Bosehedral

Artifact for paper `Bosehedral: Compiler Optimization for Bosonic Quantum Computing`

_Bosonic quantum computing, based on the infinite-dimensional qumodes, has shown promise for various practical applications that are classically hard. However, the lack of compiler optimizations has hindered its full potential. This paper introduces Bosehedral, an efficient compiler optimization framework for (Gaussian) Boson sampling on Bosonic quantum hardware. Bosehedral~overcomes the challenge of handling infinite-dimensional qumode gate matrices by performing all its program analysis and optimizations at a higher algorithmic level, using a compact unitary matrix representation. It optimizes qumode gate decomposition and logical-to-physical qumode mapping, and introduces a tunable probabilistic gate dropout method. Overall, Bosehedral significantly improves the performance by accurately approximating the original program with much fewer gates. Our evaluation shows that Bosehedral can largely reduce the program size but still maintain a high approximation fidelity, which can translate to significant end-to-end application performance improvement._

## Installation

Requirements:

* Linux x86-64 server
* 32GB RAM, 50GB disk
* Python 3.10

To install Python packages:

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

## Execute

See our appendix for more instructions on notebooks and results.

## Cite

```bibtex
@misc{zhou2024bosehedral,
      title={Bosehedral: Compiler Optimization for Bosonic Quantum Computing}, 
      author={Junyu Zhou and Yuhao Liu and Yunong Shi and Ali Javadi-Abhari and Gushu Li},
      year={2024},
      eprint={2402.02279},
      archivePrefix={arXiv},
      primaryClass={quant-ph}
}
```
