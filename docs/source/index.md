# Welcome to stEDGE's documentation!

## Edge-guided multiscale reconstruction of hierarchical spatial domains and transition interfaces in spatial transcriptomics

```{toctree}
:maxdepth: 1
:caption: Contents:

Installation
Tutorial_1_step_by_step
Tutorial_2_Crohn
Tutorial_3_HBC
Tutorial_4_Cere
Tutorial_5_Lung
```

```{image} Figures/Overview.png
:width: 100%
:align: center
```

## Overview

**stEDGE** is an edge-guided and interpretable framework for reconstructing multiscale tissue architecture from spatial transcriptomics data. Instead of treating tissues as flat spatial partitions, stEDGE explicitly models local boundary probability and domain transition intensity to distinguish stable compartments from transition-rich interfaces.

The stEDGE workflow includes boundary probability modeling, edge-guided domain reconstruction, transition-aware hierarchy construction, and tree-guided gene program interpretation. Together, these components allow stEDGE to recover fine-grained spatial domains, organize them into coarse-to-fine tissue hierarchies, and link spatial states to multiscale gene programs.

stEDGE produces structured outputs including multiscale spatial domain labels, boundary probability, domain transition indices, domain graphs, hierarchy trees, and multiscale gene programs. These outputs support downstream analysis of stable compartments, directional transition zones, nested tissue hierarchy, and branch-specific molecular programs.

## Citation

If you use stEDGE in your work, please cite:

He, Y. **stEDGE enables edge-guided multiscale reconstruction of hierarchical spatial domains and transition interfaces in spatial transcriptomics**. 2026.

Citation information will be updated upon publication.

