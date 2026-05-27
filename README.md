<p align="center">
  <img src="./docs/source/Figures/Logo.png" alt="stEDGE logo" width="30%">
</p>

# stEDGE Tutorials

[![Documentation Status](https://readthedocs.org/projects/stedge-tutorials/badge/?version=latest)](https://stedge-tutorials.readthedocs.io/en/latest/)

This repository contains tutorial documentation for **stEDGE**, an edge-guided framework for multiscale reconstruction of hierarchical spatial domains and transition interfaces in spatial transcriptomics.

**Documentation:** <https://stedge-tutorials.readthedocs.io/en/latest/>

## Tutorials

The documentation includes installation instructions and five tutorial notebooks:

- **Tutorial 1:** Mouse embryo MOSTA data — step-by-step walkthrough of the full stEDGE workflow
- **Tutorial 2:** Crohn's disease Visium data
- **Tutorial 3:** Human breast cancer Visium data
- **Tutorial 4:** Mouse cerebellum Slide-seqV2 data
- **Tutorial 5:** Human fibrotic lung Xenium data

## Getting started

### Prerequisites

- Python 3.10+
- [stEDGE](https://github.com/yihe-csu/stEDGE-main) installed (see main repository for instructions)

### Install dependencies

```bash
pip install -r requirements.txt
```

### Download data

The tutorial notebooks expect data files in a local `data/` directory. Download the datasets from the links below and place them under `data/`:

| Tutorial | Data directory |
|----------|---------------|
| Tutorial 1 | `data/Mouse_embryo/` |
| Tutorial 2 | `data/Crohn_disease/` |
| Tutorial 3 | `data/Human_Breast_Cancer/` |
| Tutorial 4 | `data/Mouse_Brain/` |
| Tutorial 5 | `data/Lung/` |

Data download links will be provided upon publication.

### Configure paths

Before running a notebook, adjust the `file_fold` and `output_dir` variables at the top of each notebook to point to your local data and output locations.

### Open the notebooks

```bash
jupyter lab docs/source/
```

## Build documentation locally

```bash
cd docs
pip install -r requirements.txt
make html
```

On Windows:

```powershell
cd docs
.\make.bat html
```

Open `docs/build/html/index.html` in your browser.

## Main repository

The main stEDGE code repository: <https://github.com/yihe-csu/stEDGE-main>

## Citation

If you use stEDGE in your work, please cite:

He, Y. **stEDGE enables edge-guided multiscale reconstruction of hierarchical spatial domains and transition interfaces in spatial transcriptomics**. 2026.

Citation information will be updated upon publication.
