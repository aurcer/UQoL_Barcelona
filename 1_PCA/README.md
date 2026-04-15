# UQoL Indicators in Barcelona 2025 - PCA

## Overview
This repository contains the R Notebook used to compute Principal Component Analysis (PCA) weights and composite UQoL dimension indices for Barcelona neighbourhoods. The analysis is part of a PhD dissertation examining the relationship between tourism impacts and urban quality of life.

## Repository structure
```
├── UQoL_PCA_Barcelona.Rmd              # This notebook
├── Indicators PCA_Neighbourhood data.csv  # Input data (required)
└── Results/                            # Created automatically on first run
    ├── Economic/
    ├── Healthcare/
    ├── Housing/
    ├── Infrastructures/
    ├── Mobility/
    ├── Social/
    ├── Urban/
    └── Aggregated/
```

## How to run
1. Place this notebook and `Indicators PCA_Neighbourhood data.csv` in the same directory.
2. Open the notebook in RStudio.
3. Run all chunks in order (Ctrl+Alt+R / Cmd+Alt+R).
4. All outputs are saved automatically under `Results/`.

## Requirements
- R version: 4.4.2
- The following packages are installed and loaded automatically if missing:

- dplyr (1.1.4)
- extrafont (0.19)
- factoextra (1.0.7)
- FactoMineR (2.11)
- ggcorrplot (0.1.4.1)
- ggplot2 (3.5.1)
- ggpubr (0.6.0)
- haven (2.5.4)
- here (1.0.2)
- openxlsx (4.2.8)
- psych (2.4.12)
- readxl (1.4.3)
- reshape2 (1.4.4)
- scales (1.3.0)

## Computational environment
- Platform: x86_64-w64-mingw32/x64
- Operating system: Windows 10 x64 (build 19045)
- README generated: 2026-04-15 18:52:17

## Citation
If you use or adapt this code, please cite the associated dissertation:
[Author, Year, Title, Institution — to be completed before submission]
