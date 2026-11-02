# DEMG-NFCA synthetic study

Code and results for the paper "A Concept Drift Index for Neutrosophic Formal Concept Analysis with Data-Driven Scaling and Two-Score Attribute Screening" (Thathappagaari and Kaspar S).

## What is here
- `DEMG_NFCA_synthetic_study.ipynb`: 12 cells. Cells 1-8 generate the synthetic data and run all studies, cell 9 prints a summary, cells 10-12 build Tables 11-16 and Figs. 4-9.
- `results/`: raw per-run records (`round1`, `sens`, `noise`, `calib`, `scale`) and `stats.json`, the numbers quoted in the paper.
- `figures/`: all figures of the paper as vector PDF.

## How to run
1. Install Python 3 with `numpy` and `matplotlib`.
2. Open the notebook in Jupyter and run the cells from top to bottom. It takes about 2 to 3 minutes.
3. The notebook writes its own `results/` and `figs/` folders.

All data are generated from fixed random seeds (1000-1029, 2000-2019, 3000-3019, 5000-5011, 7000-7019), so the numbers are the same on every run. Only the timings in Table 14 depend on the computer.

## Licence
MIT licence for the code. Add your own copyright line before publishing.
