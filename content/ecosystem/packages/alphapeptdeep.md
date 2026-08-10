---
title: "alphapeptdeep"
description: "Advanced data-independent acquisition (DIA) analysis for proteomics experiments"
date: 2024-01-15
---

**alphapeptdeep** is a cutting-edge software tool for analyzing data-independent acquisition (DIA) mass spectrometry data. It provides researchers with advanced algorithms and intuitive workflows for comprehensive proteome analysis.

AlphaPeptDeep is a Python framework which allows users to build models to predict any desired property of peptides from scratch with only a few lines of code. Our framework uses a flexible chemical composition encoding for PTMs, thus supporting all UniMod and user-defined modifications. Based on this framework, we built state-of-the-art models to predict fragment intensities, retention time and ion mobility of peptides. The package is built on the open-source and widely used [pytorch](https://pytorch.org) framework, enabling developers to easily extent and build upon our tools.

## Applications 
With transfer learning, it can well predict spectral libraries for multiplex-DIA ([Thielert  et. al. 2022](https://www.biorxiv.org/content/10.1101/2022.12.02.518917v1)). By using AlphaPeptDeep, we can easily build a model to predict what HLA peptides are present for individuals ([Wahle et al, 2024](https://doi.org/10.1016/j.mcpro.2023.100689)), and then predict personalized spectral libraries to boost HLA-DIA identifications. 




- [**GitHub**](https://github.com/MannLabs/alphapeptdeep)
- [**Documentation**](https://alphapeptdeep.readthedocs.io/en/latest/)
- [**Publication**](https://doi.org/10.1038/s41467-022-34904-3)
