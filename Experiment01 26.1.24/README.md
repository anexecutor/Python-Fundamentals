# Python Fundamentals

## Experiment 01: Data-driven Optimization

This experiment demonstrates a simple data-driven optimization method using random sampling.

## Environment
- Python 3.10.12
- ipykernel
- JupyterLab
- numpy
- matplotlib
- pandas

## Files
- experiment01.ipynb
Jupyter Notebook version, used for interactive experiments and visualization.

## How to run
```bash
Open experiment01.ipynb directly in VS Code and run cells interactively.

## Environment Setup (Recommended)
```bash
conda create -n pyfund python=3.10.12
conda activate pyfund
pip install ipykernel jupyterlab numpy matplotlib

### Objective Function
f(x) = x^2 + 3 sin(x),  x ∈ [-10, 10]

### Method
Randomly sample candidate solutions and select the best one based on data