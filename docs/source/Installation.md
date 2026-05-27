# Installation

`stEDGE` is a Python package for edge-guided multiscale reconstruction of hierarchical spatial domains and transition interfaces in spatial transcriptomics.

`stEDGE` does not require GPU acceleration. The package is designed to run in a standard Python environment and supports multi-core parallelization for computationally intensive steps such as multi-resolution clustering, consensus matrix construction, and graph-based analysis.

To ensure smooth installation and execution, we recommend installing `stEDGE` in a clean conda environment.

## 1. Installation from GitHub

Open a terminal or command prompt and clone the stEDGE repository:

```bash
git clone https://github.com/yihe-csu/stEDGE-main.git
cd stEDGE-main
```

Install the required dependency packages:

```bash
pip install -r requirements.txt
```

Install `stEDGE` from source:

```bash
pip install -e .
```

You can test whether the installation was successful by running:

```python
import stEDGE
print(stEDGE.__version__)
```

## 2. Anaconda environment

For convenience, we recommend using a separate conda environment for running `stEDGE`.

Create a conda environment named `stEDGE`:

```bash
conda create -n stEDGE python=3.12.5
```

Activate the environment:

```bash
conda activate stEDGE
```

Then clone and install `stEDGE`:

```bash
git clone https://github.com/yihe-csu/stEDGE-main.git
cd stEDGE-main
pip install -r requirements.txt
pip install -e .
```

## 3. Use stEDGE in Jupyter Notebook

To use the `stEDGE` environment in Jupyter Notebook, JupyterLab, or VS Code, add it as a Python kernel:

```bash
pip install ipykernel
python -m ipykernel install --user --name=stEDGE --display-name "Python (stEDGE)"
```

When opening the tutorial notebooks, select the kernel:

```text
Python (stEDGE)
```

## Notes

Some steps in `stEDGE` involve clustering, graph construction, and numerical optimization. Small variations may occur across software environments. For reproducible results, we recommend using a fixed random seed and a consistent Python environment.