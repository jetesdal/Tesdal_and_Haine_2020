# Tesdal_and_Haine_2020
ECCOv4 based freshwater and heat budget analysis of the Subpolar North Atlantic Ocean and Nordic Seas from 1992 to 2015

This repository contains the analysis code for [Tesdal and Haine (2020)](https://doi.org/10.1029/2020JC016435). The study uses the[ECCOv4](https://www.ecco-group.org/home.cgi) reanalysis product and compares budget variability and mechanisms within the subpolar North Atlantic Ocean, Nordic Seas, and Labrador Sea from 1992 to 2015.

## Summary
This study presents a comprehensive analysis of freshwater and heat budgets for the subpolar North Atlantic Ocean and Nordic Seas, using the ECCOv4 reanalysis product and dataset. The study focuses on the period between 1992 and 2015 and provides an understanding of the variability and mechanisms that drive these budgets in these regions.

## Analysis Code
The repository contains the following Jupyter Notebooks:
- `eccov4r4_output.ipynb`: This notebook is used to build the zarr dataset from ECCOv4 output.
- `eccov4r4_budgets.ipynb`: This notebook is used to build the zarr dataset of volume, heat and salt budgets.
- `fig1.ipynb`, `fig2.ipynb`, ...: These notebooks show how to produce each figure in the paper.
- `tab1.ipynb`, `tab2.ipynb`, ...: These notebooks show how to produce each table in the paper.
- Additional notebooks are included that are used to produce interim datasets used to generate the figures.

## Dependencies
The code in this repository is written in Python and requires the following libraries to be installed:
- numpy
- xarray
- matplotlib
- cartopy

## Usage
To run the code in this repository, you will need to have Jupyter Notebook or Jupyter Lab installed, and python version 3.7. Once you have Jupyter installed, you can open the notebooks in this repository and run the code cells.

## Data
Please see "Data Availability Statement" in [Tesdal and Haine (2020)](https://doi.org/10.1029/2020JC016435) for how to access the ECCOv4output and any ancillary datasets used in this study. ECCOv4 output was reproduced follwoong the instruction presented in [Wang (2019)](https://www.ecco-group.org/docs/v4r4_reproduction_howto.pdf).

## Reference
If you use this code or data, please cite the following paper:
- Tesdal, J.-E., & Haine, T. W. N. (2020). Dominant terms in the freshwater and heat budgets of the subpolar North Atlantic Ocean and Nordic Seas from 1992 to 2015. Journal of Geophysical Research: Oceans, 125, e2020JC016435. https://doi.org/10.1029/2020JC016435
