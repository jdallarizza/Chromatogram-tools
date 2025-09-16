# Chromatogram Tools

Python scripts for generating and visualizing chromatograms from SEC (Size Exclusion Chromatography), IMAC, or IEX data. Designed for use in Jupyter Notebook.

## 📦 Features

- Plot absorbance curves, % buffer B, conductivity, etc. using `matplotlib`
- Annotate peaks automatically with `scipy.signal`
- Highlight collected fractions with shaded regions
- Estimate molecular weight according to calibration curve for the corresponding column (SEC)
- Modular and customizable plotting function
