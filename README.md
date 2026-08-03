# Nuclear size and physical properties of the nucleoplasm are determined by colloid osmotic pressure at the nuclear envelope

This repository contains the analysis code used in this preprint, including scripts to extract segmentation data from Morphometrics (Matlab).

## 🚧 Still Under Construction
The code does not fully work yet — I'm still working on uploading everything.
## Manuscript
- [Preprint on bioRxiv](https://doi.org/10.64898/2026.07.21.739918)

All scripts can be run directly in **Google Colab**, so there is **no need to install Python locally**.

## Authors
Joël Lemière\* (1), Zhidong Tan (1), Fred Chang\* (1)

(1) Department of Cell and Tissue Biology, University of California San Francisco, San Francisco, CA 94117, United States

\*co-corresponding authors

## Description of files and folders

**`Data/JL396EMM_1/`**

This folder contains three example raw data files (TIFF images of cells) and two subfolders named `Data` and `Analyzed`.
`Data` contains:
- Phase contrast images of one replicate (42 cells total), named `PhaseJL396.tif`
- The output from [Morphometrics](https://doi.org/10.1186/s12915-017-0348-8) on the cell segmentation stack: `PhaseJL396_05-Jun-2025_CONTOURS_pill_MESH.mat` and `PhaseJL396_05-Jun-2025_CONTOURS.mat`
- The CSV table of cellular volume measurements from the 42 cells TIFF file: `JL396-1.csv`
- The CSV table of all combined measurements (date, volumes, intensity, replicates#, Strain#,..) from the 42 cells TIFF file: `JL396-1+Nuc.csv`

`Analyzed` contains:
This folder contains three examples of the analysis output (CSV and TIFF formats), including nuclear volume and fluorescence intensity measurements.
