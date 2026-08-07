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
- factoextra (1.0.7)
- FactoMineR (2.11)
- ggcorrplot (0.1.4.1)
- ggplot2 (3.5.1)
- ggpubr (0.6.0)
- ggrepel (0.9.6)
- haven (2.5.4)
- here (1.0.2)
- openxlsx (4.2.8)
- psych (2.4.12)
- QCA (3.23)
- readxl (1.4.3)
- reshape2 (1.4.4)
- scales (1.3.0)

## Computational environment
- Platform: x86_64-w64-mingw32/x64
- Operating system: Windows 10 x64 (build 19045)
- README generated: 2026-08-05 09:30:31

## Citation
If you use or adapt this code, please cite the associated dissertation:
[Author, Year, Title, Institution — to be completed before submission]
