
# Python Fundamentals

## Experiment 8: Surrogate-assisted Evolutionary Optimization

This experiment aims to minimize a noisy objective function using an evolutionary algorithm assisted by a surrogate model.

## Environment
- Python 3.10.12
- ipykernel
- JupyterLab
- numpy
- matplotlib
- pandas
- scikit-learn

## Files
- experiment08.ipynb
Jupyter Notebook version, used for interactive experiments and visualization.

## How to run
```bash
Open experiment05.ipynb directly in VS Code and run cells interactively.
```

## Environment Setup (Recommended)
```bash
conda create -n pyfund python=3.10.12
conda activate pyfund
pip install ipykernel jupyterlab numpy matplotlib scikit-learn
```

### Objective Function
f(x) = (x-2)**2 + noise ,  x ∈ [-5, 5]