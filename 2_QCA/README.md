# UQoL Indicators in Barcelona 2026 - QCA

## Overview
This repository contains the R Notebook used to perform a fuzzy-set Qualitative Comparative Analysis (fsQCA) on the composite UQoL dimension scores for Barcelona neighbourhoods. The analysis examines which configurations of UQoL dimensions, in combination with the tourism context, are associated with high and low perceived residential satisfaction. This analysis is part of a PhD dissertation examining the relationship between tourism impacts and urban quality of life.

## Repository structure
```
├── QCA_UQoL_Barcelona.Rmd                           # This notebook
├── ../1_PCA/Results/Aggregated/                     # Input data (from PCA step)
└── Results/                                        # Created automatically
    ├── Calibration/
    ├── Necessity/
    ├── Sufficiency/
    ├── Tourism_mapping/
    └── Plots/
```

## How to run
1. Ensure the PCA notebook has been run first and the aggregated CSV is available.
2. Place this notebook in the project directory (as a sibling to the `1_PCA` folder).
3. Open the notebook in RStudio.
4. Run all chunks in order (Ctrl+Alt+R / Cmd+Alt+R).
5. All outputs are saved automatically under `Results/`.

## Requirements
- R version: 4.4.2
- The following packages are installed and loaded automatically if missing:

- admisc (0.38)
- dplyr (1.1.4)
- extrafont (0.19)
- ggplot2 (3.5.1)
- ggrepel (0.9.6)
- here (1.0.2)
- QCA (3.23)

## Computational environment
- Platform: x86_64-w64-mingw32/x64
- Operating system: Windows 10 x64 (build 19045)
- README generated: 2026-10-31 14:40:00

## Citation
If you use or adapt this code, please cite the associated dissertation:
[Author, Year, Title, Institution — to be completed before submission]
