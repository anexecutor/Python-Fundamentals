
# Python Fundamentals

## Experiment 7: Basic Evolutionary Algorithm for Continuous Optimization

This experiment implements a basic (μ + λ)-Evolutionary Algorithm (EA) to solve a continuous optimization problem.

## Environment
- Python 3.10.12
- ipykernel
- JupyterLab
- numpy
- matplotlib
- pandas
- scikit-learn

## Files
- experiment07.ipynb
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
f(x) = sin(2*pi*x) + noise ,  x ∈ [0, 2]

### Methods
- Population initialization 种群初始化
- Fitness evaluation 适应度计算
- Elitist selection 精英选择
- Gaussian mutation 高斯变异
- Iterative evolution 迭代进化