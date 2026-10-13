# The Forgotten Bias of SIRENs: A Theoretical Analysis of Sinusoidal Network Initialization — companion notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rozen92/forgotten-bias-sirens/blob/main/siren_initialization_figures_notebook.ipynb)

This repository contains  `siren_initialization_figures_notebook.ipynb`, which reproduces
all the figures and numerical values of the paper *The Forgotten Bias of SIRENs: A Theoretical
Analysis of Sinusoidal Network Initialization*.


## Requirements

Python 3.10+ with `numpy`, `scipy`, `matplotlib`, `pandas` and `jupyter`:

```bash
pip install numpy scipy matplotlib pandas jupyter
```

## Usage

```bash
jupyter nbconvert --to notebook --execute siren_initialization_figures.ipynb
```

or open the notebook and run all cells. A full run takes about 5 to 8 minutes on a laptop CPU.
The figures are written as PDF files to `figs/`.

