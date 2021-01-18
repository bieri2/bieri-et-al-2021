# Impacts of large-scale soil moisture anomalies on the hydroclimate of South America
## DOI: 10.1175/JHM-D-20-0116.1

This repository includes a suite of Jupyter notebooks used to complete analysis for Impacts of large-scale soil moisture anomalies on the hydroclimate of South America (Bieri et al. 2021). For details of the analysis, please see the publication, linked here: https://doi.org/10.1175/JHM-D-20-0116.1.

There are four notebooks included in this repository. A brief decription of each is provided below. 

Please contact bieri2@illinois.edu with any questions about this code. 

<b>read_redata.ipynb</b>: Script to read MERRA-2 or ERA5 reanalysis files. 

<b>eof_func.ipynb</b>: Script with functions to complete extended EOF analysis. 

<b>run_eof.ipynb</b>: Script to read reanalysis data and perform EOF analysis. To run this script, read_redata.ipynb and eof_func.ipynb must be available in the same directory. 

<b>analyze_cesm_output.ipynb</b>: Script to read CESM model output, apply processing steps, and plot results. 
