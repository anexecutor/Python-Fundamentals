# Python Fundamentals

## Experiment 02: Surrogate-based Optimization

Minimize a non-convex function using a data-driven surrogate model.

## Environment
- Python 3.10.12
- ipykernel
- JupyterLab
- numpy
- matplotlib
- pandas

## Files
- experiment02.ipynb
Jupyter Notebook version, used for interactive experiments and visualization.

## How to run
```bash
Open experiment01.ipynb directly in VS Code and run cells interactively.
```

## Environment Setup (Recommended)
```bash
conda create -n pyfund python=3.10.12
conda activate pyfund
pip install ipykernel jupyterlab numpy matplotlib
```

### Objective Function
f(x) = x^2 + 3 sin(x),  x ∈ [-10, 10]

### Method
1. Random sampling to collect initial data
2. Polynomial regression as surrogate model
3. Optimization on surrogate
4. Evaluation on true function

### Result
The surrogate-guided solution achieves better performance than random sampling.